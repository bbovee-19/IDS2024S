**1** .md stands for "mark down". If I remeber correctly we prefer to use mark down because it's easier to work with compared to others.  
**2** Yes  
**3** Yes  
**4** The purpose is contain your project and any changes made to it.   
**5** cd means change directory to your home directory.   
**6** ls -a means list all.   
**7** pwd tells you who's account is being used, or the current directory.  
**8** Working Directory - When changes are being made to a project.  
      Staging Area - is a file area where a project is saved to later be commited permanently.  
      Commit Stage - this is where and when a project file is commited and changes are saved to the repository permanently.  
**9** VCS is a type of system that helps keep track of a file/files and changes made to them. 
**10**The benefits of a distributed VCS    
      1. Everyone can have a clone of the central database.  
      2. Collaboration is possible.  
      3. No potential loss of data.  
      4. Can work independently on the same thing.  
      5.  
      6.  
**11** Local, Centralized, and Distributed VCS.  
**12** Git is a DVCS where you can edit projects and push it to GitHub, which is VCS.  
**13** git status does exactly that, it brings up the status of your current project. 
**14** git push --all will push your project and all of its branches to your remote repository.  
**15** git pull will pull the latest revision of a project from the remote to your local repository.  
**16** Markdown is a way to style your text.   
**17** To make a text bold face you use double asterisks in between your words.  
**18** Similar to making a text bold, you only use one asterisk to make text italic.  
**19** git init  
**20** A singular "." means that you want to go back to the previous directory, or the "parent" directory.
Double ".." means you want to go to the previous previous directory, or similary the "grandparent" directory.  

germa@LAPTOP-NN98J96R MINGW64 ~
$ pwd
/c/Users/germa

germa@LAPTOP-NN98J96R MINGW64 ~
$
germa@LAPTOP-NN98J96R MINGW64 ~
$ mkdir testdir

germa@LAPTOP-NN98J96R MINGW64 ~
$ cd testdir

germa@LAPTOP-NN98J96R MINGW64 ~/testdir
$ ls -a
./  ../  
To "testdir" a Git project I'd have to go back and make a git repository using git init and put testdir in there.  
