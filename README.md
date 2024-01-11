# Google-Apps-Script-Forms-Docs
Pulls data from a Form to a Doc via Sheets.
Makes a Doc from a template.
Fills in the merge fields on the Doc from the spreadsheet that stores the Form responses.
If an answer on the Form was blank, the Doc changes the merge field to a blank.
Names the Doc "(Job Name) Checklist".
If the Job Name folder exists, the new Doc gets saved there.
If the Job Name folder doesn't exist, the script creates it and saves the new Doc there.
