# GitHub Tutorial

_by: Stella R. LaPorta_

---
## Git vs. GitHub
* Git: version control = "snapshots" of code; helps track progress
    * Git does not require Github
*Github: a cloud/program on the internet that stores your code - [github.com](https://github.com/)
    * Github requires Git

---
## Initial Setup
* If you don't have a Github account or not using anything cloud-like you can use a one time setup command of `git config`, this is allow you to title your work and commits   
        * `git config --global user.name Your Name`: Sets a 1 time only global username to title your work  
        * `git config --global user.email YourName@email.com`: Sets a 1 time only global username to attach to your work  
* Once you have created a Github account you can connect it with either Cloud9(c9) or Nitrous  
    * To connect websites take the SSH Key from the website (local machine) and connect it to your account.  
    * Every time you Save, Add, Commit and Push it will go to the cloud (Github)  

* To Save on Cloud9 you can set it to automatic save 
        * If you want to manually save go to File then click Save and make sure the circle turns into an x  
* Next you would Add your code to the Stage by doing `git add .` or `git add --all` to get ready to commit  
* After Adding you then would have to use `git status` to see if it committed properly.  
    
    * When you do git status you should get a message that says:
    
    
    * Once you see the green you can now commit it and to commit it you would use:  
    The message that should go between the quotes should be short and sweet, to show what you have done and what that command did `git commit -m "Your message"`  
    * Once it has been committed you will see:  
    
        * Type in git log to see if it was committed, at that time you will see your message to yourself and the time you committed it.  
        
        *you will have to type in the command `git log` in order to see  
      
    * Finally when it is committed you can do `git push` or `git push origin master` in order to push your committed work up to the cloud (or what system your using)

---
## Repository Setup
* In order to make a repository through the command line:
    * create folder using `mkdir name-of-repo.md`
    * use `cd folder-name.md` to go into that directory or folder
    * Create file but doing `touch ReadMe.md`
    * Type `git init` to begin tracking your progress by turning it into a repository
* Once made repository through the command line:
    * If using Github with either cloud9 you would have to go to github and go to the + next to your icon then it will say Create New if hovered over it but when you click it you will see the words "New repository" and "New organization"
    * Click New repository and it will give you the options:
    
* Once you have created the repository on github and added it to your local machine (c9 or Nitrous) you can do:
            `git push origin master` or even `git push`  

####**This will then cause the file that has been saved, added and commited to be pushed up to the cloud (local machine)**

---
## Workflow & Commands

**`git init`**  
    * Opens repository within your current folder, WARNIN: always cd into the folder you want to initilatize before typing in `git init`  
**`git status`**(optional)  
    * Helps to see the last file that was committed  
        * Red =last commit was edited  
        * Green =Staged and ready to commit  
**`git add --all`**  
    * Puts everything in current repository onto the stage to be ready to committed  
**`git commit -m`**  
    * -m :allows you to attach a message to the snapshot  
    * Allows you to take snapshot of your code to get ready to be pushed up to the cloud  
**`git push`**  
    * pushes all changes that have been added and committed up to the cloud to be publicly display
**`git pull`**  
    *Used during collaboration to pull down other changes that have been pushed up to the cloud to see what they have added or edited  
**`git log`**  
    * Once you have saved added and committed you can type in git log in order to see all of your commits and the messages along with them  
**`git diff`**  
    * Shows you the difference between the current code you have now and what was last committed  
**`git remote -v`**  
    * Allows you to see which remote repository's are currently attached to your local machine  
**`git clone`**  
    * Used to clone a copy of someone else's repository but not be able to push it and mix it with their code  
    