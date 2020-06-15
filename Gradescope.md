# GradeScope

GradeScope is a tool that is used to automate testing of student homework submissions. It is very flexible and allows you to write your own test scripts and provide your own Docker image. By default a Docker image is used which runs Ubuntu 18.04 as of this writing. Libraries are included which support writing tests in Python, Java and C#. You can read their [documentation on the technical aspects](https://gradescope-autograders.readthedocs.io/en/latest/specs/). We are developing libraries to support other languages and updates on those will be able to be found on this page as they are added.

## Canvas and GradeScope

Ecampus provides guidance on [getting GradeScope synced up with a Canvas course](https://learn.oregonstate.edu/faq/what-gradescope). This will get your GradeScope account and your Canvas account linked and sync up the course roster. Note that while you can select a GradeScope type assignment by choosing it as an external tool when creating an assignment, this does not actually create individual GradeScope assignments and should be avoided. Instead follow the directions on the Ecampus page to create assignments in GradeScope and in Canvas then link the two.

## Grade Script Setup

The area where new users of GradeScope tend to see the most trouble is in the area of creating the correct file hierarchy. The important files are [listed here](https://gradescope-autograders.readthedocs.io/en/latest/specs/#autograder-specifications). The important thing is to make sure that that `setup.sh` and `run_autograder` are both in the *root* of your archive that you submit. It is easy to accidentally put everything in a directory and then add the directory to an archive. This will generate errors when submitted to GradeScope. Instead of selecting the directory to add to an archive, make sure to enter the directory and directly archive all the files.

## Integrating with GitHub classroom
If you are using GitHub classroom, you will want to give permissions to the clasroom organization before your students can submit projects which were created using any of the GitHub classroom assignments.

To do that make sure you have admin/ownership privileges over the GitHub classroom organization and then follow the instructions in [this GitHub documentation](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/requesting-organization-approval-for-oauth-apps) for GradeScope while looking for your classroom organization in Step 5 there.

## Language Specifics

This portion of the guide will focus on issues specific to different languages. Currently the only supported language used by the program is Python. SQL, C and JavaScript are coming soon.

### Python

The [official documentation](https://gradescope-autograders.readthedocs.io/en/latest/specs/) does a good job describing the basics of the Python library. However, there are a few things that are easy to miss.

#### 2.7 vs 3+

By default the scripts all run `python`. If you are used to Windows or any package manager that assumes that `python` should download and install the latest version of Python, you will encounter some unexpected results. The default Ubuntu image's package manager assumes that `python` means Python 2.7. If you want Python 3 you need to install `python3` and when you run python you need to run `python3`. The same goes for `pip` and `pip3`.

#### unittest msg Parameter

The Python `unitttest` module is well documented at the [official Python site](https://docs.python.org/3.7/library/unittest.html). One feature that isn't very well documented is the additional `msg` argument that can be passed to the assert functions. For example the definition for `assertEqual` is `assertEqual(first, second, msg=None)`. But most people don't use the `msg` argument and just rely on the default output from `assertEqual`.

`msg` is actually very powerful for student learning. You can help craft more specific error messages. For example, if you were testing the base case of a merge sort you might run an assert like `assertEqual(len(mergesort[5]),1)`. But if the student returned an empty list the error message they would see would simply be `Test Failed: 0 != 1`. At the very least a message like `f'Merge sort test failed: When a single element list is passed into mergesort a single element list should be returned. Your function returned a list of length {len(mergesort[5]))}'`. This provides the student much more context and provides a more detailed explanation of what happened. If this is passed as the `msg` parameter they will see the message for failed tests on the results page of GradeScope.

