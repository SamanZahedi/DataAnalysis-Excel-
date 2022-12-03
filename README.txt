Dataset Used in this Assignment
The dataset used in this lab comes from the following source: https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr under a Public Domain license.

The dataset is related to inventory information about the fleet of vehicles. The data is in comma-separated value (CSV) format and the data also needs cleaning up before you can start to run any kind of analysis on it.



Guidelines for the Submission
Download the file Montgomery_Fleet_Equipment_Inventory_FA_PART_1_START.CSV. Upload and open the file with Excel for the web and convert it to an .XLSX file. Then clean the data as detailed below.

Use the course videos from Module 3 and the lab ‘Hands-on Lab 5: Cleaning Data’ to help you complete these tasks.

Tasks to perform:

Save the CSV file as an XLSX file: Click the 'Edit Workbook' button in the ToolTip to save the file as an XLSX file. The file is converted when you click 'OK' in the prompt.

Column widths: Sort out the widths of all columns so that the data is clearly visible in all cells.

Empty rows: Use the Filter feature to look for blanks and remove all empty rows from the data.

Duplicate records: Use either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.

Spelling: The original source file data has not been checked for errors in the spelling. Check for spelling mistakes in the data and fix them.

Whitespace: Use the Find and Replace feature to remove all double-spaces from the data.

Department names: When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Use Flash Fill to reduce the department names to just one column, and then remove any unnecessary columns.

Department	Department
Board of Elections	Economic Development
Circuit Court	Environmental Protection
Community Engagement Cluster	Finance
Community Use of Public Facilities	Fire and Rescue
Consumer Protection	General Services
Correction and Rehabilitation	Health and Human Services
County Executives Office	
Save your workbook: Use 'Save As' to save your completed workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.XLSX





Format the data as a table: Use the Format as Table option to format the data as a table.

Use AutoSum to calculate values: Use AutoSum to find the following values for column 'C' and record each of the values:

SUM
AVERAGE
MIN
MAX
COUNT

Create a Pivot Table: Use the PivotTable feature to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

Sort the pivot table data: Use the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.
Add the Equipment Class field below the Department field so that the different vehicle types appear under each department with their respective counts.
Collapse all fields except the top one

Save your workbook: Use 'Save As' to save your workbook as Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.XLSX