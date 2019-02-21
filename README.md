# timesheet-manager
Printer-friendly timesheet with associated database


## How it works
This timesheet worksheet is great to record timesheet hours in a printer-friendly format and be able to save and access them in a database. The spreadsheet has a simply formated Database sheet in the backend to store your data, and will read this database when you click the 'Save' button.

### Functions
#### Save
Click this button to save the current spreadsheet data to the database. The Status will change from Unsaved to Saved.

#### Date
Changing the date will load in the data for the associated week. If you have unsaved changes, you will be prompted before proceeding.

## Customising
If you make changes to the spreadsheet outside the code, be sure to check the global variables in the Timesheet module before running. These variables are the main connections between sheet formatting and the code, so changing the spreadsheet requries updating of these variables.
