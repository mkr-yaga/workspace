DevOps workspace
# workspace

Hello friends we will start from here.
# Git setup for beginners in Ubuntu OS.


* All the commands will be executed as root user so please be careful.
* If you want to execute as another user please add SUDO before the commands. 


The same we should do with cloud servers.
# login to your system using your credentials.

This command will update and upgrade your system.
# $ apt update && apt upgrade

to check whether git is available or not in your machine.
if git is not present in your machine then.
# $ git 

to install git in your system.
# $ apt install git

to check the version of git.
# $ git --version

Here we will start configuring our git.
# Now installation is complete. Let's configure our git

Here we will provide the username of our git account.
# $ git config --global user.name "YOURUSERNAME"

Here we will provide the email address which is integrated with the git account.
# $ git config --global user.email "EMAIL"

This will list out the credentials set up in our machine.
# $ git config --list

The basic commands will start here to push the file.
# Now let's start working with git and push a file into the repository.

Here we are creating a sample folder for the git repository.
# $ mkdir git-folder

now we have gone inside the git folder.
# $ cd git-folder/

This will initialize an empty git repository.
# $ git init

This will create 1.txt file.
# $ touch 1.txt

This will show how many files are needed to be staged for the git online repository.
# $ git status

This will add 1.txt to the staging path.
# $ git add 1.txt 

This will commit the file with comments.
# $ git commit -m " The file has been committed"


## Now we will initialize a token that is required for the Linux machine to push the files on the online git repo.

# goto Git login >> git email & passed >> setting >> Devloper Setting >> Tokens >> create claasic token >> copy tocken and save it.

git remote add origin https://<token>@github.com/<username>/<repo>.git
# Note >> Git token will only be shown once please copy it and save it to use further. 

This command will push 1.txt to the main branch.
# $ git push origin main 











