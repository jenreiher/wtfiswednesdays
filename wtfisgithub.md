#WTF is Github?!

Git is all about making little bundles that represent a change. 
Github is a server service that uses git. 

A commit is a "unit of work". It represents the difference between two files. It allows you to go back in time if you need to - you don't throw away your work. It's never gone. 

git status < ALL THE TIME! it will tell you what's going on and lets you know if you need to push your changes.

stage > git add <thing>
e.g. git add /file/thing/this.txt
or git add . <---- every file ever

git ignore = types of files you don't want to upload (e.g. draft file types)

git commit -m "my messssssage so I remember wtf I was doing" > put this online and make a 'marker' of the change. this is your "save point." 

git commit --amend > dangerous but helps you save face for typos :) use with caution! 

your most recent commit is called your "head".

cherry pick

conflicts - merges and cherry picks

why working on master is bad - master should be your VERY BESTY self. each commit represents a version. 
master master (server) vs master (local machine)

pull request is a github terminology. master pulllllls the change in

*How to set up a new branch to work on: git checkout -b dev --track origin/master*
* git = using git
* checkout = switch between branches
* -b = create a new branch
* dev = name of the branch is going to be dev
* -- track = create a link between this branch and another branch
* origin = the server version
* master = name of the branch to link it to


call your local branch something else for the sake of safety. push/sync that up to the server on a copy of that branch.
once it's on the server then make the pull request to merge it into master. then, delete that branch. 

git branch -vv > tells you everything about your branches and how they are linked

git push origin dev
// pushing to the server on a branch called dev

then make the pull request from the user interferace 

###forking

if there are conflicts you can modify to create a hybrid

if there is a conflict fix local & then clean it up before pushing

###rebasing

works, but not everyone agrees. can be dangerous! have good practice in place to prevent issues. 

git pull rebase --i

undoes your commits, updates master branch and then replays your commits as part of the timeline. it will check for conflicts. 

master > test > production







##Resources Produced
* [GitHub Commandline for Beginners] (https://docs.google.com/document/d/15YxJv7vAX5HFPUx7s3TQT-JUT-IbcTyHXoWt4tC_Bk8/edit?usp=sharing)



##Learning Tools
### Explanations
* [Visual guide] (http://marklodato.github.io/visual-git-guide/index-en.html)
* https://guides.github.com/introduction/flow/
* http://think-like-a-git.net/


### Tutorials
* [Awesome commandline git tutorial from CodeSchool] (https://www.codeschool.com/courses/try-git)
* https://www.codecademy.com/learn/learn-git
* https://guides.github.com/activities/hello-world/
* http://rogerdudler.github.io/git-guide/


### Quick Reference Guides
* [Github markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* https://help.github.com/
