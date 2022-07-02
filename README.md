# git-and-github-aid
Helps me remember initial git and github setup.  
This **README** is also used to get familiar with *Markdown* syntax.

### Setup

**On local computer, in terminal, any directory**  
*we do the below because I'm going to use SSH, honestly don't what it mean **yet**.*  
$ ssh-keygen -t rsa -b 4095 -C "email@addr.com"  
$ cat ~/.ssh/id_rsa.pub *this line outputs the SSH key into the terminal for you to see*  
*copy the output on the terminal, and paste it Github's Settings -> SSH and GPG keys -> New SSH key*  

*the below 2 steps should only be done once per computer*  
$ git config --global user.name "name"  
$ git config --global user.email "email@addr.com"


**On local computer, in terminal, inside work directory**  
$ git init  
$ git add .  
$ git status *this is optional*  
$ git commit -m "Commit message"  

