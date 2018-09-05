# Terminal-stuff
# I am going to be saving all the stuff that I learn about terminal in this repo.

## Cloning a project using URL
Type 'git clone [Your Project Url]' in your terminal. Make sure you are in the folder that you want to save your project in. 

## Staging all your changes before commiting.
Type 'git add .' ### or 'git add -A' and it'll stage all the changes that you made in your file and get it ready for you to push. 

## Committing your changes
If you are committing the first time do so by 'git commit -m "your message". After that you can just type 'git commit' on your terminal to commit the changes.

## See the status of your git
To see the status of your project using the terminal you can do by typing 'git status' in the terminal

## See the directiory path of your project from your terminal.
To see the directiory path of your peoject you can see the path by typing 'git remote -v' on your terminal. It'll show you the path of 'push' and 'fetch'. In other words you can see where your code is going from your terminal.

## To change the directiory of your peoject
If you ever change anything in your github repo, your project will create a new URL path for your project. you'll have to direct your peoject to the new URl path. However, before doing that you need to remove the other path of your project to your github. You can do so by 'git remote rm origin' then do 'git remote -v' to see what the directiory is. Then add the new url with the following 'git remote add origin [your new url]' and to see if it has changed you can do so by typing this 'git remote -v'.

## Push your code to github from your terminal
To push your code to github first time you can do so by doing this 'git push -u origin master' once the first push is done you can just push easily usinig 'git push'

###
