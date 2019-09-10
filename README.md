first step

$ git config --global user.email "your email"

$ git config --global user.name "your username"


see how Git is configured

$ git config --list


local directory

$ git init 

$ echo "Hello, world!" >> README.md 

$ git add README.md

$ git commit -m "README.md upload"

$ git remote add origin https://github.com/user/repository.git

$ git remote set-url origin git@github.com:user/repository.git

$ git status

$ git push -u origin master 


management

$ git status

$ git add your file

$ git commit -m "Comments"

$ git push -u origin master


undo changes to unstaged files

$ git checkout -- filename


accidentally mistype a commit message

$ git commit --amend -m "New message"


revert addition

$ git reset


syncing a local directory with an existing git repository

$ git pull


delete local and remote directory

$ git pull

$ git rm -r directory

$ git commit -m "Removing directory"

$ git push -u origin master


cloning repository

$ git clone git://github.com/user/repository.git

$ git remote set-url origin git@github.com:user/repository.git


shows the remote's URLs

$ git remote -v


view a repository's history

$ git log


view a specific file's history

$ git log path


switch from one branch to another

$ git branch

$ git checkout branch-name


create a branch

$ git checkout -b branch-name


merging two branches

$ git merge branch branch


brand new repository

$ git init project-name

shows the commit ancestry graph

$ git show