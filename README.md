# PowerShell and Git 

### PowerShell

A shell is the outermost interface exposing an OS's service to a human user and allowing them to manipulate it.

###### PowerShell commands

- $PSVersionTable - Grabs the version table
- cd ~ (tilde)  - goes back to home directory
- cd .. (double dot) - goes up one folder
- cd ..\\.. - goes up two folders
- cd / - goes to root folder
- ls - lists all files and folders in current directory
- md [foldername] - makes a new folder in the current directory
- notepad [filename] - makes a new notepad with file name as [filename]
- cat [filename] - concatenate files and prints the output
- copy [target filename] [destination filename] - copies contents of target to destination
- mv [target filename] [destination folder] - moves target file to destination folder
- del [target filename] - deletes file
- Get-Alias - lists all prefix syntax and displays its shorthand description

###### PowerShell ISE

PowerShell Integrated Scripting Environment. Allows you to run commands, write, test and debug scripts.

- Get-Command \*dns* | Out-GridView - displays a new window with all the commands listed 

PowerShell scripts use the extention [.ps1] . Inside the scripts themselves are powershell commands

Initially, running the script may give an error. This is due to your execution policy.

- Get-ExecutionPolicy [-list] - grabs the current execution policy for the current user, -list displays all available execution policies
- Set-ExecutionPolicy -Scope [User] -ExecutionPolicy [Execution Policy] - sets the execution policy for a user to the assigned execution policy

------



### Git

Git is a version control system. GitHub is a distributed version of version control.

All git commands begin with git

###### Git commands

- init - initialises a local repository within the current directory
- status - displays current status of the repository (which branch you're on, what files are ready for commits)
- add [filename] - moves file name to staging area (one step before committing)
- commit --m "[message]" - commits files in the staging area into a snapshot of the current stage

