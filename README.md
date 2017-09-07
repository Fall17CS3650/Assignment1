# Assignment1

# First-Name Last-Name

TODO - Update  your name in this readme

Description:

In this assignment, you will practice getting setup for the course. 

1. Get a CCIS Linux account if you don't already have one.
2. Test your login by ssh'ing into the server on your platform. 
3. Create a github account 
4. Get practice using github 
5. Program Tasks

# CCIS Linux Account

You can request a CCIS linux account from the following page: 

https://my.ccs.neu.edu/account/apply#_ga=2.179726500.1824142048.1503529620-438635994.1493401748

A welcome page and additional information is located here if you are new to Northeastern--welcome!
http://www.ccis.northeastern.edu/current-students/masters-and-certificate/new-students/

# Login to NEU server

ssh is a protocol that allws you to login and access resources remotely. 

If you are running on a linux or mac,  you can use ssh through the terminal. If you are on Windows, I recommend downloading a program called Putty.

ssh yourname@login.ccs.neu.edu (where yourname is your ccis account)

You will then be prompted to enter a password (Note the password characters are not echoed back as you type).

# Creating a github account:

GitHub(www.github.com) is an online webpage that hosts git respositories. GitHub.com is a place that will host your code online where you can make incremental changes to. Your code will be saved online, and you can then download the repository from anywhere!

1. Log onto https://github.com
2. Create a new account
3. Accept the invitation to this assignment by clicking the assignment on the course page or on this link: https://classroom.github.com/a/41YYMJn-

# Get practice using github 

Practice using git (the version control program that uploads your code to github.com) through the following tutorial:

https://try.github.io/levels/1/challenges/1

# Get practice with the commandline.

If you are not currently experienced with the terminal, you should get some practice.

Here are some commands to run in the terminal.

Tasks:
    
    mkdir cs3650
    cd cs3650
    mkdir ps1
    cd ps1
    man git
    
    Next we will clone the repo from git onto the server. This is where you can work from.
    
    git clone "https://github.com/Fall17CS3650/Assignment1-your_user_name_here"
    
    Once you have cloned in the repo to the CCIS server, you may then edit this README document with your name.
    Once you have done so, then commit your changes to the repo.
    
Next task:
    
    Try some of these commands:
    ls
    man ps
    ps
    ps -ef
    
    You may additionally try other commands.
    
    When you are satisfied, pipe the output from your terminal into a text file called "playground.txt".
    
    When you have done this, add the "playground.txt" to the repo, and commit your changes.
    
    Your assignment will then be graded (I have a neat script that clones all repos for me) from whatever exists on the repo on the 19th just before class starts.
