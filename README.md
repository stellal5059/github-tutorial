# GitHub Tutorial

_by: Stella R. LaPorta_

---
## Git vs. GitHub
* Git: version control = "snapshots" of code; helps track progress
    * Git does not require Github
*Github: a cloud on the internet that stores your code
    * Github requires Git

---
## Initial Setup
* Once you have created a Github account you can connect it with either Cloud9(c9) or Nitrous
    * To connect websites take the SSH Key from the website (local machine) and connect it to your account.
    * Every time you Save, Add, Commit and Push it will go to the cloud (Github) 

* To Save on Cloud9 you can set it to automatic save 
        * If you want to manually save go to File then click Save and make sure the circle turns into an x
* Next you would Add your code to the Stage by doing `git add .` or `git add --all` to get ready to commit 
* After Adding you then would have to use `git status` to see if it committed properly.
    
    * When you do git status you should get a message that says:
    
    
    * Once you see the green you can now commit it and to commit it you would use:
    The message that should go between the quotes should be short and sweet, to show what you have done and what that command did 
    `git commit -m " "`
    * Once it has been committed you will see:
    
        * Type in git log to see if it was committed, at that time you will see your message to yourself and the time you committed it.
        
        *you will have to type in the command `git log` in order to see 
      
    * Finally when it is committed you can do `git push` or `git push origin master` in order to push your committed work up to the cloud (or what system your using)

---
## Repository Setup
* To set up a repository you can do one of two things:
    * If using Github with either cloud9 you would have to go to github and go to the + next to your icon then it will say Create New if hovered over it but when you click it you will see the words "New repository" and "New organization"
    * Click New repository and it will give you the options:
    
* Once you have created the repository on github and added it to your local machine (c9 or Nitrous) you can do:
    ```git push origin master``` or even ```git push```  

####**This will then cause the file that has been saved, added and commited to be pushed up to the cloud (local machine)**
---
## Workflow & Commands
