[Home](/README.md)

## Terminal Commands

`cd` - Change Directory  
`ls` - List all items in the directory  
`pwd` - Present Working Directory  
`cd` .. - go back a level in the directory  
`touch file.html` - Create a new html file named "File.html"  
`mkdir myFolder` - Create a new folder named "My folder"  
`cp file.html ../myFolder` - copy the file myfile.html into the folder myFolder that is located one directory back  
`mv file.html ../myfolder` - move the file myFile.html into the folder myFolder that is located one directory back  

*everthing is in relation to where we are starting

# Sharing Code

- Understanding git
- sharing code and collaboration: dvcs for the masses
- version control system
- lets multiple devs work on the same code
- history of changes to your filoes
- ability to view, apply, and remove those changes
- keep all project files in one repository (folder)
- it makes collaboration possible

## Snaphots in time

- each succesive version creates a new snapshots on the timeline of the project
- git keeps track of what file looked like at different times
- each commit (snapshot) has a label that points to it
- HEAD: the label meaning “You are Here"
- usually you give a snaphot a label called a message
- A->B->C

## GitHub

- not git
- a way to share code with others
- and online place to store your code
- it uses Git to help you manage your team’s work
- version tracking
- review changes
- keep changes separare until you want to add them in

## Git + GitHub = Awesome

with Git (version control) and GitHub (online code storage), you can:

- have lots of team members work together on the same files, without messing each other up
- keep a history of each file over time
- work on code on your computer and sysnc it with what is online

## What is a repository?

- a repository is a collection of files that you’ve told Git to pay attention to
- usually, one project = one repository
- really large projects might have multiple repositories for different parts of their system (ie: front end vs. back end)
- repositories can live on GitHub and/or your computer

## Linking Repos

- copy repo from GitHub to our computer
-nclick on code button for repository and copy link
- enter `git clone` and paste link in terminal
- `git status` show changes we made
- `git add .` adding changes
- `git commit -m “added new file and updated a couple more”` explaining changes
- `git push origin main` publish the changes from origin(local) to main (GitHub)

## Lab

- Clone GitHub to computer
- revise reading-notes
- homepage to contain intro and table of contents [day 1](markdown) etc.
- push to GitHub
