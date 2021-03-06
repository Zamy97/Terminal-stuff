# Terminal-stuff
# I am going to be saving all the stuff that I learn about terminal in this repo.

## Cloning a project using URL
Type **'git clone [Your Project Url]'**  in your terminal. Make sure you are in the folder that you want to save your project in. 

## Staging all your changes before commiting.
Type **'git add *'** or **'git add -A'** or **'git add .'** and it'll stage all the changes that you made in your file and get it ready for you to push. 

## Committing your changes
If you are committing the first time do so by **'git commit -m "[your message]"**. However, make sure to add a message everytime you commit or else it might get messed up.

## See the status of your git
To see the status of your project using the terminal you can do by typing **'git status'** in the terminal

## See the directiory path of your project from your terminal.
To see the directiory path of your peoject you can see the path by typing **'git remote -v'** on your terminal. It'll show you the path of 'push' and 'fetch'. In other words you can see where your code is going from your terminal.

## To change the directiory of your peoject
If you ever change anything in your github repo, your project will create a new URL path for your project. you'll have to direct your peoject to the new URl path. However, before doing that you need to remove the other path of your project to your github. You can do so by **'git remote rm origin'** then do **'git remote -v'** to see what the directiory is. Then add the new url with the following **'git remote add origin [your new url]'** and to see if it has changed you can do so by typing this **'git remote -v'**

## Push your code to github from your terminal
To push your code to github first time you can do so by doing this **'git push -u origin master'** once the first push is done you can just push easily usinig **'git push'**

## Get rid of a foler and a file in your project
To get rid of the unnecessary files do the following in the terminal **'git rm --cached [your file name]'** it'll get rid of that file in your repo project. 
To get rid of a folder in your repo you do the following: **'git rm -r --cached [your folder name]'** 
In addition you can do **'git rm -r [your folder name]** and **'git rm [Your file name]'** that will get rid of the folder and file from your project.

## Add gitignore file in your project
To make sure you are not pushing the sensitive stuff on github, you can add a gitignore file in your project and it'll not push everything on github.

## Create a file using the terminal
To create a file in your project do the following **'touch [Filename]'**. Make sure you are in the right folder and creating the file where you want it to be. 

## Create a folder in your project
To create a folder in your project you can do so by doing the following: **'mkdir [Folder name]'**. Make sure you are in the right project and you are creating your folder where you want it to be. 


## Going backward in the terminal
To see what the previous folder you were in you can see that by trying the following **'cd ..'**.

## See what's inside a folder
To see what you have inside a certain folder you can do the following: **'ls'** in your terminal. And It'll list all the visible that you have inside of something that you are trying to see. To see the hidden files in your project do: **'ls -a'** and it'll show you eveything in your project.

## See the working directiory
To see what the directiory you are in you can see the whole path by typing the follwoing in your terminal: **'pwd'**. Which stands for **"Print Working Directiory"**

## Reset your terminal
To reset your terminal you can do so by typing the follwoing: **'ctrl + c'**

## Open a new tab in your terminal
To open a new tab in your terminal you can type **'CMD + T'** and it'll open up a new tab in your terminal.

## Open a file using your terminal.
To open a file using your terminal, navigate to your file and type in ex: **'atom [.Filename]'**. It should open up the file where you want it to open. 

## Something to keep in mind about the '$' in your terminal.
Type everying after **'$'** sign. Remember: Don't include the $ in your command. In addition, Whenever you see the $ in a command, that means it should be called in your computer's terminal.

## Add a local project to an empty repo on Github.
You can add your local project to github remotely instead of cloning the project. To do so do the following: 
*  Creat your project in your local computer.
* Type **'git init'** on your terminal to create a git file in your project. Make sure you are in the right folder.
* Type **'git add -A'** to stage everything to get it ready to commit.
* Now create an empty repo on Github with a similar name. Don't name it the same as your project. It'll be confusing moving forward.
* Copy the **URL** of that empty repo.
* Type **'git remote add [project URL]'** in your terminal, It'll connect your local project to github empty repo.
* To push code for the first time. Type **'git push origin master -u'** and it'll push every single changes in your github.

## Commit a specific file 
To commit a specific file you do the following: **'git add [File name]'** {you could do more than one}  -> **'git commit -m "[Message]"**

## Open up finder with the current working directiory
To open your current working directiory using the terminal do the following: **open .**

## Create bullet points on anywhere
Do **option + 8** to create a list using bullet points.

## Get out of the python interpreter from the terminal
To get out of the python interpreter type **exit()** in your terminal and it'll exit out of it. 

# A bit about Pytest!

## Test a specific method
To test a specific method type **File_name.py::test_method_name**

## See what passes and stop at the first failed method.
To see what methods passes and let the test stop at the first failed one type: **pytest -v -x file_name.py**

## To get all the details about the pytest
Do: **pytest -v file_name.py**

## Test one specific file:
type: **pytest file_name.py**

## Stop at the first failed method in a specific file.
Type: **pytest -x file_name.py**

## Git pull from a remote( github repo ) to your local repo on your computer
If you make any changes on another computer and want to pull the changes in your local repo your 'git pull origin' might not work! so you have to do **git pull origin master --allow-unrelated-histories** and then **git push -u origin master**

## Create a Branch on your project!
To create a new branch on your project use **git checkout -b develop** this will create a branch call **develop**

## Push the changes to your branch
If you make any changes on your branch you will have to push them to your branch. Make sure to do **git add .** then **git commit -m "something"** then **git push origin [your branch name]**

## Switch Branch
To switch branch you can do the following command **git checkout master** and this will take you to **master** branch.

## Merge a branch with master
To merge your branch with the master you can do the following command: **git merge [your branch name] ex: develop**

## See all the branches 
To see all the branches that exists in your project type the following command: **git branch** and it'll show what branch you are on as well all the other branches that exists in your project. To get out of it press **q**

## Vim stuff
To use the vim and type in stuff inside a file wihtout opening atom you can do **vi [file name]** then press **i** to insert text then press **esc** to get out of it and then hold **shift** then press **zz** that will get you out of the program and get you back to the terminal. 

## See your command history
Type history in your terminal and you should be able to see all the commands that you have types in there. 

## Run a python3 file in the python interpreter
To open your python file in the interpreter run this command **python3 -i [File_Name]**

## Tests the doc-tests from your file in the pyton interpreter
To tests whether if the doc-tests passes by providing some value run this command **python3 -m doctests [File_name]** To see details of the doc tests run this command **python3 -m doctest -v [File_name]**
