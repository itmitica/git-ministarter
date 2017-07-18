# Git commands

## Master branch

### Choose push method, if not already chosen
    $ git config --global push.default simple

### Create remote repository
github.com -> new repository

### Clone locally
    $ git clone https://github.com/itmitica/more-clocks.git
    $ cd more-clocks`

### Make changes then push
    $ git add .
    $ git commit
    $ git push origin



## Working with branches

### Create a branch
    $ git branch -d somebranch

### Choose the branch
    $ git checkout somebranch

### Make changes then push
    $ git add .
    $ git commit
    $ git push origin somebranch


### Go back to master
    $ git checkout master

