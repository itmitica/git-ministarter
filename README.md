# git-ministarter
Basic git cli steps

install git
> sudo apt-get install git


configure user and email
> git config --global user.name "itmitica"
> git config --global user.email "itmitica@gmail.com"


initialize in the desired local project folder
> git init

create .gitignore file and add rules: *.bak, *.exe, *.o, app binary e.g. laddiso
> touch .gitignore

remove ignored files created prior to .gitignore creation
> git rm --cached *.bak
> git rm --cached -r lib/
> git rm --cached laddiso

either

> git clone https://github.com/itmitica/laddiso.git
to create "origin" remotes
and locally add all branches to sync with

or

add remote github repository to the desired local project folder
> git remote add laddiso https://github.com/itmitica/laddiso.git

pull remote files, to the desired local project folder,
in case there are files not existent locally
> git pull laddiso master


if there are changes of the project files in the local folder where you run git
> git add .


commit changes to the desired local project folder
> git commit


push local files to remote project github repository
> git push laddiso master


