# GIT commands

## New repo commands
create a new repository on the command line
```
echo "# Mydoc---GitHub-Actions-" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Shabareeshsa/Mydoc---GitHub-Actions-.git
git push -u origin main
```
…or push an existing repository from the command line
```
git remote add origin https://github.com/Shabareeshsa/Mydoc---GitHub-Actions-.git
git branch -M main
git push -u origin main
```

## Git Installation Commands
```
$ brew install git	Install Git with Homebrew on Mac OS
$ sudo port selfupdate	Install Git with MacPorts on Mac OS
$ sudo apt-get install git	Install Command for Linux
$ git –version	Shows the current version of your Git
```

## Git Configuration & Setup

```
git config --global user.name "Fabio"	Set your username globally.
git config --global user.email "signups@fabiopacifici.com"	Set your email globally.
git config –global color.ui auto –	Set to display colored output in the terminal
git config --list get the config details
```
>Use global to set the username and e-mail for every repository on your computer. If you want to set the username/e-mail for just the current repo, you can remove global

## Initializing a Repository 
```
git init	Initializes a new Git repository in the current directory.
git init <directory>	Creates a new Git repository in the specified directory.
git clone <repository_url>	this Clones a repository from a remote server to your local machine.
git clone –branch <branch_name> <repository_url>	Clones a specific branch from a repository.
```
