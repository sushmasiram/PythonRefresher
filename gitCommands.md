#### Day26-Github:

###### create a local git configuration for our account



```
git config --global user.name "sushmasiram"

git config --global user.email "sushma.motamarri@gmail.com"
```



###### Files navigation in cmd prompt

dir: list the items of current location

pwd: present working directory

mkdir: make a new directory

cd: change a directory



###### clone a repo to local

git clone https://github.com/whitehatjr/bouncyBall

git status - To see any new updates that are to be commited

git log - To see history of the repo

git add .   Adds all the files that are edited

git commit     commits the changes

This updates our git repo in local machine.


Now we need to associate the working directory on our git bash shell to this remote repository. 

We do this using the 'git remote add' command.

git remote add  test https://github.com/sushmasiram/test_git.git

git push -u test
