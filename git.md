# GitHub vs Git

_Git_ is a version control system tool that has the ability to manage a project or set of files related to a project, and maintains a history of the source code changes (i.e. file versions) throughout the process.  All of this information is stored in a data structure called a _repository_ (or repo), which is stored (or hosted) on GitHub, a web-based graphical interface.  It is best practice to create one repo for each project, however farely large projects may have additional subfolders.  

![Alt Text](https://toolsqa.com/wp-content/gallery/git/GitAndGithub.jpg)

The main differences between Git and GitHub are summarized in the table below:

![Alt Text](http://cdn.differencebetween.net/wp-content/uploads/2018/03/Git-VERSUS-GitHub.jpg)

*The neat thing about GitHub and Git is that when combined they create a collaborative development platform for programmers.* 

![Alt Text](https://3.bp.blogspot.com/-SnWr9oa-G30/UY6tZKwGZPI/AAAAAAAABLc/dyQGoX_i3E8/s1600/Github.png)

Another cool thing about Git which sets it apart from other version control systems is the way Git thinks about its data. Conceptually, most other systems store information as a list of file-based changes - they think of the stored information as a set of files and the changes made to each file over time.  Git on the other hand doesn’t think of or store its data this way. Instead, Git thinks of its data more like a set of "snapshots" of a mini filesystem. Every time you commit, or save the state of your project in Git, it basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. 

![Alt Text](https://git-scm.com/figures/18333fig0105-tn.png)

_(For my fellow corporate professionals these snapshots are the equivalent of a "blacklined" document. For the benefit of everyone else, this tool is a way to compare two documents in a word processing program and display only what changes have been made between them. The comparison is displayed by default in a new third document - the "blackline", which would be your snapshot.)_


## Git Command Cheat Sheet


| Command       | Usage         |
| ------------- | ------------- |
| git status  | show modified files in working directory, staged for your next commit  |
| git add [file]  | add a file as it looks now to your next commit (stage)  |
| git add .  |  - when ran after "git status" command this will add all folders / files that appeared in the result  |
| git commit -m  |  “[brief message describing why you made the changes]” - commit your staged content as a new commit snapshot |
| git push [alias] [branch]  | transmit local branch commits to the remote repository branch  |
| git push origin master  | sync code to repo on GitHub |
| git pull  | fetch and merge any commits from the tracking remote branch  |
| git merge [alias]/[branch]  | merge a remote branch into your current branch to bring it up to date |
| git rm [file] | delete the file from project and stage the removal for commit  |
| git mv [existing-path] [new-path]  | change an existing file path and stage the move |
| git log --stat -M | show all commit logs with indication of any paths that moved  |
| git clone [url]  | retrieve an entire repository from a hosted location via URL  |
