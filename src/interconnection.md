# Connection between the components

Issues arising from the connection between the components could mean one of many things: 

1. The data being sent from the Form to the sheet is invalid, and / or the data being loaded from the sheet into the program may be invalid. This could be due to modifications of the form or sheet, which resulted in some incorrect values present in the sheet (such as an incorrectly-entered date or count of inventory). 
2. The Visualizer attempting to access an Excel sheet that has either been downloaded (and is thus not synced to Sharepoint and may be outdated) or is not properly synced to the computer (the file must be available offline / locally).

Anyone who is familiar with the Microsoft Office suite should be able to fix these problems without much difficulty, and so it should not be necessary to hire an external developer.