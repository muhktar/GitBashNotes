# Command line functions,Installing chocolatey, Installing gitbash

## Installing chocolatey
Choclatey enabels you to install and uninstall applications from your Windows Powershell.
First open Windows powershell right click it and run it as an adminstrator.
Then paste this into powershell and hit enter to install choclatey:

    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

## Command line functions
* explorer .

This function makes the file explorer open

* cd (directory name)

This function changes the directory  placing you in the directory of your choice

* ls

This Function list out all the files as well as the hidden files in your current directory

* mkdir 

This function creates a directroy

* touch

Thus function creates a file 

* nano

This function enable you to add words to a file 

* cat 

This Function shows you the contents of a file

## Using chocolatey functions on powershell to install/uninstall programs:
Run powershell as an administrator and type choco install (program name) to install a program
or choco uninstall (program name) to uninstall a program. For example to install gitbash we 
would type:

* choco install (gitbash)


tab button auto completes

## Git commands (Creating Local Repository and Pushing to Remote(Online) Repository)

* git init

This command makes sure that the directory can recognize get commands by  generating a .git folder in the directory

* git add . 

This command adds everything from the current directory including changes, to the git-repository(it modifies the contents of the aforementioned .git folder)

* git commit -m  " your update message"

This commits the changes to be pushed to the web

* copy paste the git remote add to execute

* git push -u origin master 

This pushes the commited changes to the web, making them acceible online

After going through all these commands your repo will be available online on git hub

https://curriculeon.github.io/Curriculeon/lectures/version-control-systems/git/my-first-repository/content.html

# makes title big 
## makes title smaller than before
### makes title even smaller, and so on and so on(has to be .md file)
