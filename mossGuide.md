# Moss Getting Started Guide

This will be a brief guide detailing the basics of getting set up to run moss on your class' programming submissions.

## Download and Setup
1. Register for Moss  
Send an email to moss@moss.stanford.edu with any subject, but the body of the email must be **_exactly_** as follows, where username@domain.tld is the email address you want associated with the moss registration.

```bash
registeruser
mail username@domain.tld
```

2. Download the moss script you receive in the email response to your registration message and put it in the directory where you expect to execute it from.  
NOTE: If you do not receive a file in the response, you can [download moss from this page](http://moss.stanford.edu/general/scripts.html){:target="\_blank"}. You'll have to change the ID number in the file line `$userid=987654321;` to your user ID from the email response.
3. Set execute permissions for that file (`chmod ug+x moss.pl`).

## Usage

From the point above, basic moss syntax will be...

```
perl moss.pl -l LANGUAGE -c "REPORT NAME" ./SomeDirectory/*.c

-l LANGUAGE          (Select moss-supported language from list below)
-c "REPORT NAME"     (Select moss output report title)
./SomeDirectory/*.c  (List of files to run analysis on... can also be listed individually)
```
List of languages supported
```
"c", "cc", "java", "ml", "pascal", "ada", "lisp", "scheme", "haskell", "fortran", "ascii", "vhdl", "perl", "matlab", "python", "mips", "prolog", "spice", "vb", "csharp", "modula2", "a8086", "javascript", "plsql"
```

You can also have a more advanced usage, following the syntax guide provided from the script.  Here are some details.

```
perl moss [-x] [-l language] [-d] [-b basefile1] ... [-b basefilen] [-m #] [-c "string"] file1 file2 file3 

-x                  (Send queries to the current experimental server version)
-b filename         (Select base files (if files are provided to students) to exclude them from consideration)
-m #                (Select maximum times a given passage may appear before ignored)
-d foo/*.c bar/*.c  (Submissions are grouped by directory, instead of by file)
```
For more details on syntax and options check the [moss file header](http://moss.stanford.edu/general/scripts/mossnet){:target="\_blank"}.

## Analysis

Once the script runs, it'll look something like this
```
Uploading Prog2/studenta.c ...done.
Uploading Prog2/studentb.c ...done.
Uploading Prog2/studentc.c ...done.
Uploading Prog2/studentd.c ...done.
Query submitted.  Waiting for the server's response.
http://moss.stanford.edu/results/293990636
```
That URL at the end is where you'll find your report.  It won't stay live forever, unfortunately, so if you end up submitting a report and they have questions, you might have to run the script again with the same parameters to re-generate it.

The output html is a double-column list of links.  Check [this MOSS output format guide](http://moss.stanford.edu/general/format.html){:target="\_blank"} for help in reading the results.  If you click on one of the submitted file links, it'll open a side-by-side comparison of the two files.  Lines which match are specified at the top of the page, and grouped by color.  You can click the grouping at the top for it to take you to that portion in each file.
