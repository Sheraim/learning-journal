Instructions

Practice with Git
Try out the workflow from the in-class workshop with another repo.

Setup and Documentation
Clone down your learning journal repo to your local computer, so you can do all future work in VS Code.

Requirements
Review your past learning journal entries.
Correct any typos
Fix any errors
Bulk up any areas that look thin
Build out your site structure
The home page should contain only your intro, and a Table of Contents.
Each topic you’ve written about should have it’s own page
Use Markdown to create a link from the ToC to the topic’s page
Keep a clean git history
After every meaningful change, A-C-P.
Write commit messages that explain WHY you made your changes, not what the changes were.
Stretch Goals
What did this exercise teach you? Add an additional page to your learning journal site to document your learnings.

Submission Instructions
Share a link to your home page in the discussion below. Check out the sites others have made!
_______________________________________________________

# GitHub and Git

_Git_ is a version control system tool that has the ability to manage a project or set of files related to a project, and maintains a history of the source code changes (i.e. file versions) throughout the process.  All of this information is stored in a data structure called a _repository_ (or repo), which is stored (or hosted) on GitHub, a web-based graphical interface.  It is best practice to create one repo for each project, however farely large projects may have additional subfolders.  

![Alt Text](https://toolsqa.com/wp-content/gallery/git/GitAndGithub.jpg)

The main differences between Git and GitHub are summarized in the table below:

![Alt Text](http://cdn.differencebetween.net/wp-content/uploads/2018/03/Git-VERSUS-GitHub.jpg)

The neat thing about GitHub and Git is that when combined they create a collaborative development platform for programmers. 

![Alt Text] (https://3.bp.blogspot.com/-SnWr9oa-G30/UY6tZKwGZPI/AAAAAAAABLc/dyQGoX_i3E8/s1600/Github.png)

Another cool thing about Git which sets it apart from other version control systems is the way Git thinks about its data. Conceptually, most other systems store information as a list of file-based changes - they think of the stored information as a set of files and the changes made to each file over time.  Git on the other hand doesn’t think of or store its data this way. Instead, Git thinks of its data more like a set of "snapshots" of a mini filesystem. Every time you commit, or save the state of your project in Git, it basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. 

![Alt Text] (https://git-scm.com/figures/18333fig0105-tn.png)

For my fellow corporate professionals these snapshots are the equivalent of a "blacklined" document. For the benefit of everyone else, this tool is a way to compare two documents in a word processing program and display only what changes have been made between them. The comparison is displayed by default in a new third document - the "blackline", which would be your snapshot.


## Common Git Commands

*git add [file name]
*git commit -m [what changes were made]
git push origin master (syncs code to repo on GitHub)
git add . (when ran after "git status" command this will add all folders / files that appeared in the result)

# To Clone to Git

Command
git clone [URL to clone] (eg "git clone (https://github.com/Sheraim/learning-journal.git))
