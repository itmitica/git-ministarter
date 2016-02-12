# git-ministarter
Basic git cli steps

install git
> sudo apt-get install git


configure user and email
> git config --global user.name "itmitica"
> git config --global user.email "itmitica@gmail.com"


initialize in the desired project folder
> git init


add remote github repository to the desired project folder
> git remote add laddiso https://github.com/itmitica/laddiso.git


pull remote files, to local desired project folder,
in case there are files not existent locally
> git pull laddiso master


if there are project files in the folder where you run git
not yet added to the project
> git add .


commit changes to local desired project folder
> git commit


push local files to remote project github repository
> git push laddiso
