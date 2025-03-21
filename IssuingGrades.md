# Grade Submission

All students who finished the class without withdrawing need to receive a final grade.  This includes students who you have elected to offer Incomplete grades to.  Check the [Incomplete Grades Guide](Incompletes.html){:target="\_blank"} for more info on requirements and implementation of the Incomplete process.

## Pulling Data from Canvas

- The Canvas grades export process is undergoing changes. The current instructions for getting the grades file exported correctly can be found here: [Canvas: Move final (letter) grades from Canvas into MyOregonState (Banner)](https://oregonstate.teamdynamix.com/TDClient/1935/Portal/KB/ArticleDet?ID=70831){:target="\_blank"} with comments and tips below...
- If you open the resultant Excel spreadsheet and change the column header "Narrative Grade" to "Narrative Grade Comment" it will save you time later.
- Take the "Before using the tool" part seriously. Especially the "Post Grades" and "Enter Zeros" parts!
- If you wish to adjust any edge-cases (students with exceptional participation, super-close edge cases, etc) you can do that in the *Final Grades* Canvas tool or in the resultant Excel spreadsheet.

### For each student with an Incomplete grade

For any students you'll be giving [Incompletes](Incompletes.html){:target="\_blank"} to, or any students with outstanding Academic Misconduct reports...
NOTE: Be careful when adjusting grades via dropdown - it's a recipe for disaster and entering the wrong grade accidentally.

1. Adjust the final grade to I/X, where X is the letter grade that the final grade initially populated to (this is the grade they'll receive if they never complete their course materials)._
2. Follow the "Last Date of Participation" steps below

### Last Date of Participation (Students with F's and Incompletes)

- For _ONLY_ students with F-grades or Incompletes, you'll need the _Final Date of Participation_ for financial aid purposes.
- DO NOT close or refresh this page while you're working on it. It will lose all your work
- Sorting this table is not enabled, so please try not to miss any.

#### For each student with an F or an I/X grade...

1. In a different tab, from the Course **Navigation** sidebar, select **People**.
2. After the roster loads, search the student's name.
3. Pull the **Last Activity** date.
4. Return to the Faculty Grade Entry tool.
5. Enter the last date of activity for the student in the respective column in the format MM/DD/YYYY (e.g. 01/04/2019).  
   - NOTE:  The last date the system will accept is the last day of Dead Week (Friday before Finals week). This day can be found on the [Academic Calendar](https://registrar.oregonstate.edu/osu-academic-calendar){:target="\_blank"}. Enter this date for any students whose participation outlasted Dead Week.
   - NOTE:  This format is **required**. The upload will fail for students who have date entries which don't match this format.

## Uploading Grades

NOTE: The grade uploading process is undergoing changes. The current instructions for uploading the grades files correctly can be found here: [Canvas: Move final (letter) grades from Canvas into MyOregonState (Banner)](https://mysupport.oregonstate.edu/esp?id=kb_article_view&sysparm_article=KB0010600){:target="\_blank"} with detailed steps below, based on my experience.

1. Now bounce over to **Faculty Grade Entry** in [My.Oregonstate.Edu](https://my.oregonstate.edu){:target="_blank"} clicking Resources and searching in "Find Resources" for the text "Entry".
2. Sort by term to find the current term. You should see "In Progress" on the left for any sections currently allowing grade entry
3. Click on one section (multi-section uploads are not possible at this time)
4. Scroll down to verify the section is selected; student names should be visible.
5. Click on the Tools wheel at the top of the page, by your name.
6. Click where it says "Browse" (It looks like a text entry field, but isn't.)
7. Browse to the XLS file provided when you exported using the "Faculty Grade Entry" Canvas tool, then hit "Upload" and then "Continue". Note, the "Continue" button doesn't change color/emphasis based on whether or not you've uploaded the file yet.
8. If you didn't change the "Narrative Grade" column header in the XLS file to "Narrative Grade Comment", then on the "Map" step you need to manually map the "Narrative Grade" column to "Narrative Grade".
9. Repeat from step 2 for each section.

## Modifying Posted Grades

Sometimes we have a reason to modify an existing grade.  There is a period of approximately one week after the grading window closes (5pm Monday after the term ends for Fall/Winter/Spring) where we cannot make changes, but outside that window we can change a final grade at any time. To do so...

1. Access the My Oregonstate Portal by opening [MyOSU](https://my.oregonstate.edu/){:target="\_blank"}.
2. Navigate to the **Resources** tab (near the top of the page).
3. In the **Find Resources** search bar, type **Grades** and select **Change Posted Grades**.
4. Select the Term from the relevant dropdown menu, then click the Section you wish to change a grade for (it will remain highlighted in blue)
5. Select the student from the **Students** dropdown menu, then click their name in the table below (it will remain highlighted in blue)
6. Select the new grade from the new dropdown menu titled **Grade Options** and click "Submit".

## Spring Term Preliminary Grades

The University must begin the process of issuing diplomas earlier in Spring Term than the final grade data is available.  To deal with this, we have a process wherein we will issue preliminary grades about halfway through Spring Term.  These are relevant only if the student is failing. Depending on your course, you may have only a few of these or your entire class might have applied for graduation.  For smaller student groups, you may use Keyed Entry, but for larger groups it is recommended to generate a file as follows.

### Preliminary Grade Data Export

When pulling preliminary grade data, follow the [Final Grade Data](#final-grade-data) guide above, but keep **Unposted Current Grade** instead of **Unposted Final Grade**.

### Uploading Preliminary Grades

1. Access the My Oregonstate Portal by opening [MyOSU](https://my.oregonstate.edu/){:target="\_blank"}.
2. Navigate to the **Resources** tab (near the top of the page).
3. In the **Find Resources** search bar, type **Grades** and select **Spring Preliminary Grades**.
4. Select **Preliminary Grades - File Upload** or **Preliminary Grades - Keyed Entry**.
5. Select the term you wish to enter grades for.  
_NOTE: From this point on, if you wish to change the Term or Course you may click **RETURN TO MENU** once or twice, then **Term Selection** or **CRN Selection** links._
6. The page which opens is an archaic interface, but there are only a few fields which you need.
    - For **Path/Filename** select **Choose File** and select the .csv file you've been modifying.
    - You may use EITHER **Subject/Course** OR **CRN** to select the course whose grades you're uploading. If you select both, the upload will fail.
    - For **Data Item Name** and **Location** associate the columns in your .csv to the appropriate data field.  This is required only for **Student ID** (SIS User ID), **Grade** (Unposted _Current_ Grade), and **Last Attend. Date** (For F-grade students and Incompletes).
7. Click **Process File**.

## Common Issues - Changing Active Term

Occasionally the system puts you in the wrong term, or you want to view grades from a previous term. If you're in the grades interface and need to change term, select **RETURN TO MENU** and then **Term Selection** to select the relevant term.
