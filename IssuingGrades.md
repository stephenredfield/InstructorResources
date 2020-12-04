# Grade Submission

All students who finished the class without withdrawing need to receive a final grade.  This includes students who you have elected to offer Incomplete grades to.  Check the [Incomplete Grades Guide](Incompletes.html) for more info on requirements and implementation of the Incomplete process.

## Pulling Data from Canvas

### Final Grade Data

The best place to start is by downloading the grades spreadsheet from Canvas Grade Center.

1. While in _Grades_ Center_, click the **Actions** dropdown.
2. Click **Export**.  
This will download the grades as a comma-separated values (CSV) file.
3. Open the downloaded spreadsheet in the editor of your choice.
4. _(Optional)_ Delete unneeded columns  
The only data columns required for grade submission are **SIS User ID** and **Unposted Final Grade**, though it is recommended to keep **Student** as well.  
NOTE: For more information on what each column header means, see the [Canvas Grade Export Guide](https://community.canvaslms.com/docs/DOC-16545-4152813648).
The only data columns required for grade submission are **SIS User ID** and **Unposted Final Grade**, though it is recommended to keep **Student** as well to simplify adding last-date-of-attendance for students with F-grades.

### Last Date of Participation (Students with F's and Incompletes)

For _ONLY_ students with F-grades or Incompletes, you'll need the _Final Date of Participation_ for financial aid purposes. First, in the downloaded grading spreadsheet, add a column for this data.  

_NOTE: Ensure this column is not auto-formatted (in Excel, select the column, right-click, **Format Cells**, and select **Text**). If this isn't done, the date-format will be overwritten when you save the file and will not be accepted by the system for upload._

#### For each student with an F grade...

1. From the Course **Navigation** sidebar, select **People**.
2. After the roster loads, search the student's name.
3. Pull the **Last Activity** date.
4. Enter the last date of activity for the student in the respective column in the format MM/DD/YYYY (e.g. 01/04/2019).  
   - NOTE:  The last date the system accepts is the last day of Dead Week (Friday before Finals week). This day can be found on the [Academic Calendar](https://registrar.oregonstate.edu/osu-academic-calendar). Enter this date for any students whose participation outlasted Dead Week.
   - NOTE:  This format is **required**. The upload will fail for students who have date entries which don't match this format.

Repeat this process for any students you'll be giving [Incompletes](Incompletes.html) to.

_NOTE: For these students, the final grade should I/X where X is the letter grade they'll receive if they never complete their course materials._

## Uploading Grades

1. Access the My Oregonstate Portal by opening [MyOSU](https://my.oregonstate.edu/). 
2. Navigate to the **Resources** tab (near the top of the page).
3. In the **Find Resources** search bar, type **Grades** and select **Final Grades Menu**.
4. Select **Final Grades - File Upload**
5. Select the term you wish to enter grades for.  
_NOTE: From this point on, if you wish to change the Term or Course you may click **RETURN TO MENU**, then **Final Grades Menu** and finally **Term Selection** or **CRN Selection** links._
6. The page which opens is an archaic interface, but there are only a few fields which you need.
    - For **Path/Filename** select **Choose File** and select the .csv file you've been modifying.
    - You may use EITHER **Subject/Course** OR **CRN** to select the course whose grades you're uploading. If you select both, the upload will fail.
    - For **Data Item Name** and **Location** associate the columns in your .csv to the appropriate data field.  This is required only for **Student ID** (SIS User ID), **Grade** (Unposted Final Grade), and **Last Attend. Date** (For F-grade students and Incompletes).
7. Click **Process File**.

## Check for Missing Grades

It's always a good idea to check your work.  To verify there are no missing final grades...

1. **RETURN TO MENU**
2. **Final Grades Menu**
3. **View Missing Final Grades**
4. Select the Term and Submit.

## Modifying Posted Grades

Sometimes we have a reason to modify an existing grade.  There is a period of approximately one week after the grading window closes (5pm Monday after the term ends for Fall/Winter/Spring) where we cannot make changes, but outside that window we can change a final grade at any time. To do so...

1. Access the My Oregonstate Portal by opening [MyOSU](https://my.oregonstate.edu/). 
2. Navigate to the **Resources** tab (near the top of the page).
3. In the **Find Resources** search bar, type **Grades** and select **Final Grades Menu**.
4. Select **Final Grades - Change Posted Grades**.

## Spring Term Preliminary Grades

The University must begin the process of issuing diplomas earlier in Spring Term than the final grade data is available.  To deal with this, we have a process wherein we will issue preliminary grades about halfway through Spring Term.  These are relevant only if the student is failing. Depending on your course, you may have only a few of these or your entire class might have applied for graduation.  For smaller student groups, you may use Keyed Entry, but for larger groups it is recommended to generate a file as follows.

### Preliminary Grade Data Export

When pulling preliminary grade data, follow the [Final Grade Data](#final-grade-data) guide above, but keep **Unposted Current Grade** instead of **Unposted Final Grade**.

### Uploading Preliminary Grades

1. Access the My Oregonstate Portal by opening [MyOSU](https://my.oregonstate.edu/). 
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