#### Make sure you have git installed on your machine


sudo apt install git


#### Make sure to set your username and email in the git config file


git config --global user.name "username"

git config --global user.email "user@email.com"



#### To get a repository from remote to local for the FIRST time
this will create a directory in pwd called "test"


git clone https://www.github.com/ninashenoy/test.git




#### To check the status of files


git status



#### To commit changes


git commit -am "your comments"



#### To push your local changes to remote


git push origin


#### if you want to add a new file

git add "filename"

#### if you want to add all new files

git add .


