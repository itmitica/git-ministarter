# git-ministarter
Basic git cli steps

install git
> sudo apt-get install git


configure user and email
> git config --global user.name "itmitica"
> git config --global user.email "itmitica@gmail.com"


initialize in the desired local project folder
> git init


add remote github repository to the desired local project folder
> git remote add laddiso https://github.com/itmitica/laddiso.git


pull remote files, to desired local project folder,
in case there are files not existent locally
> git pull laddiso master


if there are changes in the project files in the folder where you run git
> git add .


commit changes to desired local project folder
> git commit


push local files to remote project github repository
> git push laddiso

