# Batch-job-delete-files-older-than-N-days
Delete files older than N days
Create a file and save it as .bat file and run it on taskscheduler to delete you backup file older then N days tested on windows server 2012 ans 2016
Note: you must have administrator right to run this.

/p Path      The Path to search  (default=current folder)

/m SrchMask  Select files matching the specified search mask
                default = *.*

/s           Recurse into sub-folders

/C command   The command to execute for each file.
                Wrap the command string in double quotes.
                Default = "cmd /c echo @file"

/D date      Select files with a last modified date greater than or 
                equal to (+), or less than or equal to (-),
                the specified date, using the region specific date format
                typically "MM/DD/yyyy" or "DD/MM/yyyy"
                
 /f          Force delete or read only file.
 
 /q          Quite or delete file without prompt
                
 for more info please visit 
 https://ss64.com/nt/forfiles.html
