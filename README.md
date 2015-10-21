# GitHub Tutorial

_by Jenny Feng_

---
## Git vs. GitHub

Git and Github may sound similar but there are a few differences where you can comprehend the concept of each.  

**_Git_** is a version control that consists of your basic workflow  

 * version control: a saved or 'snapshot' that keeps your code
  * so you can return to your original code if you made a mistake and want to fix it
 * no GITHUB needed for Git (2 separate devices)
 * simple commands - assists you; to save your code
 * initialize your git to begin working (git init)
  * look through workflow & commands!
  * adding files 
  * commiting your saved and added file (ability to seize and store your code)
 * a space for your command lines to run

**_GitHub_** is basically a website that people can view the work you have created. 
 
* must obtain git in order to proceed
 * explore through this website - github.com (or you can call it the cloud of the code)
* your code is stored within this website that you are presenting yourself by 
* repositories can be viewed, forked, and cloned 
 * look through workflow & commands for more information about forking and cloning


---

## Initial Setup

What is initial setup, you may ask. This is where you first begin to place your SSH key from the device you're using (nitrous, cloud 9, etc)
into Github so that viewers can see it live.

**Directions:** 

1. sign in with github and the local machine you are using
2. once signed in, continue on by clicking on settings on the dropdown menu with your profile icon
3. select "SSH keys" and press "add key"
4. name the key and copy and paste your SSH key into the large text box
  * similar to finding the previous steps; go to your local machine > settings > SSH Keys > copy and paste the default key
5. after you've added the key, you are able to run your code through github so that others can preview live of your workflow


---
## Repository Setup

In order to create a repositories, you must name your repo to something that is relavant to what your code states.  

#####For GitHub

1. Sign into github.com and your local machine, that may be Nitrous, Cloud 9, etc
2. On github.com, travel to your profile and select on 'repositories' and click on "New"
3. Type in the **EXACT** name that you typed into your local machine
 * otherwise, it would not work and would not connect to your repository 
4. Then press, "Create Repository"

####For Your Local Machine

1. Sign into your device that you are working with
2. Press on new workspace to add a new repo
3. Type a title that is simple and easy to recall
4. Then just press "Create Workspace"
 
And you are done! Well, continue creating repositories if you desire to add more



---
## Workflow & Commands

There are a lot of commands that you can run through the local machine you are operating with

_Here are a list of the relatively significant command lines that you'll use on your device_

 * **git init** - this can initialize and start your local machine
  * without this, you can use anything else below the list
 * **git status** - this allows you to see what commits, adds, or changes you've made and what you need to do to save your changes
 * **pwd** - basically assists you acknowledge where you are exactly
  * if you type in pwd and you get back '/home/ubuntu/workspace/github-tutorial' and you are meant to be in your 'about-me' then _'cd ..'_out 
 * **ls** - this will list the items your repositories contain
  * example: 
  You are in github-learning and type into the workspace, ls, and you get back
    "directions.md' & 'README.md'
 * **git add README.md** - this command line will add the file that you had just made changes to
 * **git commit -m " "** - save a snapshot of your code that you have just added
 * **cd ..** - allows you get out the repositories and return to where you were before
 * **git log** - you can see your past commits
 * **git diff** - (self-explanatory) able to view the difference between your current code and the previous commit
 * **git remote add origin URL** - you can connect your URL to the location of your remote repo (short for repositories)
  * select SSH because you've added an SSH key to your github.com account
 * **git push -u origin master** - you are able to send your commits from your local repo to your remote repo
 * **git pull** - takes any changes from the remote repo to local repo
 
**_Forking_** obtains a remote copy of someone else's remote repo
 * you DO have consent to push your changes to the original repo  
 * _remote repositories_ are 

**_Cloning_** copies of the local remote(s) of someone else's remote repo
 * you are not able to push any changes into the original remote repository  
 
 * _local repositories_ 