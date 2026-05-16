Index html accesses list of gategories and tasks from a google sheet.  
2 Factor security with a random 5 digit code assigned to a user who has to verify id with a 4 digit pim
Interactive usse interface allows students to view and update status of task
Students only view tasks assigned to them
Teacher html shows class overview of progress
Teachers must verify a completed task for 100% completion
Teachers can staus complete and verify 
Dats is stored in googles-sheets
Progress_sheet is the combined sheet
Category_List contains list of cateories
Task_Names contains the Tasks and categories
There is a fuction to popuklate the progress sheets with asignning all tasks to students- 
No Duplication
Authentocation is done is Student Names
Entire sheet is pubdlidhed as csv which is read by code.  The url of the csv is in code
code write to sheet via App Script integration (code.gs)
Every change must be redployed
Web app url for app script is written into code
Netlify is used to publis files
