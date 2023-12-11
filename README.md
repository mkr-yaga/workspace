# workspace
DevOps workspace
# Git setup for beginners in Ubuntu OS.
Hello friends we will start from here.

* All the commands will be executed as root user so please be careful.
* If you want to execute as another user please add SUDO before the commands. 

# login to your system using your credentials.
The same we should do with cloud servers.

# $ apt update && apt upgrade
This command will update and upgrade your system.

# $ git 
to check whether git is available or not in your machine.
if git is not present in your machine then.

# $ apt install git
to install git in your system.

# $ git --version
to check the version of git.

# Now installation is complete. Let's configure our git
Here we will start configuring our git.

# $ git config --global user.name "YOURUSERNAME"
Here we will provide the username of our git account.

# $ git config --global user.email "EMAIL"
Here we will provide the email address which is integrated with the git account.

# $ git config --list
This will list out the credentials set up in our machine.

# Now let's start working with git and push a file into the repository.
The basic commands will start here to push the file.

# $ mkdir git-folder
Here we are creating a sample folder for the git repository.

# $ cd git-folder/
now we have gone inside the git folder.

# $ git init
This will initialize an empty git repository.

# $ touch 1.txt
This will create 1.txt file.

# $ git status
This will show how many files are needed to be staged for the git online repository.

# $ git add 1.txt 
This will add 1.txt to the staging path.

# $ git commit -m " The file has been committed"
This will commit the file with comments.

## Now we will initialize a token that is required for the Linux machine to push the files on the online git repo.

# goto Git login >> git email & passed >> setting >> Devloper Setting >> Tokens >> create claasic token >> copy tocken and save it.

# Note >> Git token will only be shown once please copy it and save it to use further. 

git remote add origin https://<token>@github.com/<username>/<repo>.git

# $ git push origin main 
The will push 1.txt to main branch.











