# sciensano
Imports 4 csv files with Covid data into Google Sheets from the Belgian Health Institute 

Imports .csv files provided by the Belgian Health Institue Sciensano with various Covid-19 related data into Google Sheets.
As of November 2020 the ImportData() function is no longer useable because some files exceed the 2 MB limit set by Google.

Being completely new to Google Apps Script I came up with this fix.

In Google Sheets:

1. Tools / Script Editor
2. Insert code
3. Run the code
4. First time it will ask for certain permissions
5. (ignore the back to safety warning when it's for personal use)
6. In the script editor Edit / Triggers -> add triggers as you see fit to auto update your spreadsheet
