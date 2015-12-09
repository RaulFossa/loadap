Welcome to Ruby on Rails! 12.08.2015

Commands for the (command line)
# pwd >enter.(Shows the  current location inside your PC)
# open . >enter (Opens the folder from the command line)
# ls and ls -a (These commands show the folder inside your current location)
# cd .. >enter (Goes back a folder from current location)
# cd . >enter (Goes up a folder from current location) exp.cd Desktop/

"super user do" (sudo) 
"if ever get a permission error" (sudo cd Desktop/ >enter) == enter password:"pass"

Create a new application (rails new)
#MAKE SURE YOU ARE LOCATED A THE DESKTOP (cd Desktop/ >enter)
#Make sure you are ONLINE
#rail new "appname" >enter (creating folder ...run bundle install [])

#Move into the folder created. (cd "appname" >enter)
#Now you can run the server command: rails server >enter. (browser: localhost:3000)
 "make sure you are located inside the application folder. Otherwise, server won't run"

===============================================================================
New Machines only!
#Configure Github
#git config --global user.name "type here"
#git config --global user.email "type here"
# you can check the info entered by using "git config --global user.name/email"
===============================================================================
while inside the app folder!

GIT INIT/ getting ready to stage and commit. :) 
#git init >enter (this will inizialize git inside the project)
#git status>enter (this will show untracked files)
#look for DS.Store GET RID OF IT!

=====================
if .DS_Store found> 
a.drag app folder into Sublime text application.
b.click .gitignore to open.
c.add folder name to the end of the list by typing .DS_Store >save
=====================

STAGE the Files!
> git add . >enter (this adds the file to be ready to be stage)

COMMIT the Files!
> git commit -am "initial commit >enter
> now if you type "git status" (Nothing to commit! Working directory is clean)

NOW TAKE THE PROJECT UP TO GITHUB. (if you make it public, more people can help!)

#Create a repository on github.com or desktop app.
#Push exising Repository from the command line (option)
#click on SSH OPTION topscreen. :)

a. copy first line and paste in the command line >enter
git remote add origin git@github.com:RaulFossa/appname.git
b. copy second line and paste in the command line >enter
git push -u origin master (this will push your project to github) 
to see it refresh github page.


CHANGE DEAFAULT README.rdoc RIGHT AWAY!
(this allows to add info/comments about your project for others to see)
>drag appfolder into Sublime text editor (the file will open)
>right click on README.rdoc >rename>rename extension to .md >enter (for "mark down")


# [*One Month Rails*] (http://onemonthrails.com)

By [Raul Fossa] 12.08.2015













