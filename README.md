# replace-script
A6 for DevOps Class


## replace:
This is a Python script file. Used command 'chmod 700' for permissions.

### Usage:
replace 'test' 'DevOps' 'WebApp'

The replace command will go to the specified directory and iterate through to replace the orginal string with the new specified string. If the original string exists nowhere, then nothing will change. If a directory or file name includes the original string, then its name will change to the new string name in place. All files will be iterated through and if the original string is found, it will be replaced by the new string. 
This should be run after the run-test setup command has been completed.

## run-test:
This is a Python script file. Used command 'chmod 700' for permissions.

### Usage:
run-test set-up OR run-test teardown

The set-up command will create the specified test directory and all contents within. If the test directory already exists, it will wipe it and start new. The teardown command will delete the test directory and everything within it. If the test directory doesn't exist, it will print the message and delete nothing.
