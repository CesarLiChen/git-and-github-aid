# git-and-github-aid
Helps me remember initial git and github setup.  
This **README** is also used to get familiar with *Markdown* syntax.

### Setup


**On local computer, in terminal, any directory**  

*we do the below because I'm going to use SSH, honestly don't what it means **yet**.*  
$ ssh-keygen -t rsa -b 4095 -C "email@addr.com"  
$ cat ~/.ssh/id_rsa.pub  
&emsp; *above line outputs the SSH key into the terminal for you to see*  
&emsp; *copy the output on the terminal, and paste it Github's Settings -> SSH and GPG keys -> New SSH key*  

*the below 2 steps should only be done once per computer*  
$ git config --global user.name "name"  
$ git config --global user.email "email@addr.com"  
$ git config --global init.defaultBranch main  (only works with git 2.28 and above)

**On local computer, in terminal, inside work directory**  

$ git init  
$ git add .  
$ git status *this is optional*  
$ git commit -m "Commit message"  

**On Github.com website, create new repository** 

- Click on the drop down in upper right Profile icon -> Your Repositories -> Click on "New"  
- Give the repository name, public or private, etc.  
- Once done, copy the SSH link.

**Back on local computer, in terminal, inside work directory**

$ git remote add origin {SSH link you copied from Github.com website goes here, without these curly brackets}  
$ git push origin {branchName, normally 'main'}

And that should be it.

**Normal-ish Workflow**  

$ git status  
$ git add .  
$ git commit -m "Message"  
$ git push origin {branch_name} *i.e. git push origin main*

**Markdown reminder, A bit out of place I know** 

\&nbsp; - for a single space  
\&ensp; - for 2 spaces  
\&emsp; - for 4 spaces  
