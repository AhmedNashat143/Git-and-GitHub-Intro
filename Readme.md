__________ Basics ______________
git --version >> to get the version of git
pwd >> print working directory
cd  [ path]  >> changing directory
cd .. >> to move back
mkdir  [folder name]   >>  to create new directory or folder
ls  >>  to show list of all directory
touch [file name] >>  to create new file in folder

__________ copy ______________
cp -r [new_folder] [my_folder] >> mean to copy the diectory of new_folder into the directory of my_folder

cp  [new_file] [my_file] >> mean to copy the file of new_file into the file of my_file

__________ cut or remove ______________
rm -r [new_folder] >> mean to remove the diectory of new_folder
rmdir  >> to remove the empty folder

__________ move ______________
mv  [new_file] [~ path to move file into] >> to move the  new_file into path destination 

__________ options______________
date >> to print the date of now
rm --help >> to get help on specific order such as rm , cp , mv  ... etc ... 
clear >> to delete all commands on screen
history >> to retrieve all history  of git commands
exit  >> to quit or close of git bash

_____________________________git_______________________________________
git config --global user.email "ahmedrefaay6@gmail.com" 
git config --global user.name "ELZAEM_143"
 >> to make configuaration of use such as email and user name

git config --global --list >> to give list of all configs

git init >> to create new repository
ls -a >> to list all files in folder and show repository which is "hidden".

git add [Readme.md>> file name] >> to add file to repository in staging area

git commit -m "message" >> to save file to repository with message.

git log >> logs of all changes

# ELzaem modify this file 

git status >> to show if file modified # Git-and-GitHub-Intro

____________________________GitHub___________________________________

>> 1. creat a new repository into github account 
>> 2. to move/upload  local repository into Github account use commands in git bash

git remote add origin https://github.com/AhmedNashat143/Git-and-GitHub-Intro

git push origin main