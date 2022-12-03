# Getting Started with Excel for Data Analysis

## Dataset Used in this Assignment
The dataset used in this lab comes from the following source: https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr under a **Public Domain license**.

The dataset is related to inventory information about the fleet of vehicles. The data is in comma-separated value *(CSV)* format and the data also needs cleaning up before you can start to run any kind of analysis on it.



## Steps taken for cleaning the data 
The file **Montgomery_Fleet_Equipment_Inventory.csv** has been converted to **.XLSX** file using MS Excel, Then cleaned through the following steps:


1. `Save the CSV file as an XLSX file`

2. `Column widths:` Sorting out the widths of all columns so that the data is clearly visible in all cells.

3. `Empty rows:` Using the Filter feature to look for blanks and remove all empty rows from the data.

4. `Duplicate records:` Using either the Conditional Formatting or Remove Duplicates feature to look for and remove any duplicated records from the data.

5. `Spelling:` The original source file data has not been checked for errors in the spelling.

5. `Whitespace:` Through Find and Replace feature to remove all double-spaces from the data.

6. `Department names:` When the data was converted from its data source, the department names (see correct list below) didn’t import correctly and they are now split over two columns in the data. Flash Fill is used to reduce the department names to just one column, and then any unnecessary columns has been removed.

### The cleaned dataset is saved as Montgomery_Fleet_Equipment_Inventory_PART_1.xlsx



## Steps taken for Analyzing the data 
Below steps has been completed:
1. `Format the data as a table:` Using Format as Table option to format the data as a table.

2. `Use AutoSum to calculate values:` AutoSum to find the following values for column 'C' and record each of the below values:

 1. SUM
 2. AVERAGE
 3. MIN
 4. MAX
 5. COUNT

3. `Create a Pivot Table:` The PivotTable feature is used to create a pivot table that displays the Department field in the Rows section, and the Equipment Count in the Values section, so that the pivot table displays the sum of equipment count by department.

4. `Sort the pivot table data:` Using the Sort By Value setting on the pivot table to sort it in descending order by the sum of equipment count.
The Equipment Class field is added below the Department field so that the different vehicle types appear under each department with their respective counts.

### The Analyzed dataset is saved as Montgomery_Fleet_Equipment_Inventory_PART_2.xlsx