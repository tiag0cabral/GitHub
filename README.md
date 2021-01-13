first step

```sh
$ git config --global user.email "your email"

$ git config --global user.name "your username"
```

see how Git is configured

```sh
$ git config --list
```

local directory

```sh
$ git init 

$ echo "Hello, world!" >> README.md 

$ git add README.md

$ git commit -m "README.md upload"

$ git remote add origin https://github.com/user/repository.git

$ git remote set-url origin git@github.com:user/repository.git

$ git status

$ git push -u origin master 
```

management

```sh
$ git status

$ git add your file

$ git commit -m "Comments"

$ git push -u origin master
```

undo changes to unstaged files

```sh
$ git checkout commit-id -- filename
```

accidentally mistype a commit message

```sh
$ git commit --amend -m "New message"
```

revert addition

```sh
$ git reset
```

syncing a local directory with an existing git repository

```sh
$ git pull
```

delete local and remote directory

```sh
$ git pull

$ git rm -r directory

$ git commit -m "Removing directory"

$ git push -u origin master
```

cloning repository

```sh
$ git clone git://github.com/user/repository.git

$ git remote set-url origin git@github.com:user/repository.git
```

shows the remote's URLs

```sh
$ git remote -v
```

view a repository's history

```sh
$ git log
```

view a specific file's history

```sh
$ git log path
```

switch from one branch to another

```sh
$ git branch

$ git checkout branch-name
```

create a branch

```sh
$ git checkout -b branch-name
```

merging two branches

```sh
$ git merge branch branch
```

brand new repository

```sh
$ git init project-name
```

shows the commit ancestry graph

```sh
$ git show
```

delete a branch

```sh
$ git branch -D branch
```

store your passwords

```sh
$ git config credential.helper store
```

shows the difference between staging and working directory

```sh
$ git diff
```