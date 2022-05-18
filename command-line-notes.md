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

touch creates file 
mkdir makes directror

nano makes you able to add words to a file 

cat shows contents of a file

### on powershell to install programs:
choco install (program name)
choco uninstall (program name)
* we installed gitbash*
tab button auto completes



git init makes sure that the directory can recognize get commands

git add .  means add everything from the current directory

git commit -m  " your commit name/dexcription"

copy paste the git remote add to execute

git push -u origin master 

after these your repo will be online

https://curriculeon.github.io/Curriculeon/lectures/version-control-systems/git/my-first-repository/content.html

# makes title big 
## makes title smaller than before
### makes title even smaller, and so on and so on(has to be .md file)
