# Text Editor vs Integrated Development Environment (IDE)

It is important to choose the most appropriate tool for a job, and for developer sometimes this means making a decision between using an integrated development environment (IDE) or a text editor.

## Text Editors

A text editor only does as its name describes and allows writing and making changes to plsin text. Text editors are also useful for removing formatting, font styles and hyperlinks from text, which can be accomplished using the default text editors for Windows (NotePad) or Mac (TextEdit); however, if you’re trying to create complex software or websites, a more advanced text editor can make the process much easier as these aren’t sufficient for advanced web developers and projects. 

Fortunately, there is no shortage of alternatives, and below is a list of some more advanced third-party options, most of which are also free:

*Notepad++
*Text Wrangler
*BB Edit
*Visual Studio Code
*Atom
*Brackets
*Sublime Text

## Integrated Development Environment (IDE)

In contrast, an IDE is a more sophisticated software that has complementing features meant to help web developers accomplish tasks with higher productivity, such as compilers, debuggers, static analyzers, contextual code completions, and project navigation/overviews, etc. 

The right tool to use will depend on a number of factors and some other pros and cons for each include: 

| Text Editor     | IDE  |
| ------------- | -------|
| Most computers already come with a pre-installed text editor, e.g. MAC has TextEdit and Windows has Notepad | Requires a system install |
| Downloads quickly and requires less memory  | Requires more memory than text editors
| Allows you to practice solely writing code and become more adept at the skill  | Supports unconscious competence and speeds up workflow, thanks to built-in shortcuts|   
| | Better suited for extensive development projects  |
|   | Often required if you are working with proprietary tooling (eg. Visual Studio)

At the end of the day, the best solution for you is one that matches the scope of the job and makes you feel at ease while diving into the work. If the built-in text editor falls short in fulfilling your needs, then simply research the options for other advanced editors or IDEs that will work with your operating system.  

As a developer the choice of using an editor or IDE is an important one and should not be a one-time decision.  You should always be re-evaluating your choices and making changes wherever needed as new software is being created all the time and current software is always being updated, therefore you will definitely miss out on awesome new features if you limit yourself to only one tool.

# Command Line Interface (cli)

The Command Line Interface (cli), also called *The Terminal*, is a program on your system that allows you to enter commands 
by typing them on the keyboard and text feedback will appear on the screen. These command "prompts" can be used to create and delete files, run programs, and navigate through folders and files.  On MAC the program is called **Terminal**, on Windows it's called **Command Prompt**.

## **Command and Shortcut Cheat Sheet**

| Command       | Usage  |
| ------------- | -------|
| pwd   | print working directory, ie. get the current path
| ls   | list current directory contents
| ls -a | list the contents of a directory, including hidden files
| cd -   | change directory
| mkdir [sample-dirname]   | make directory
| touch [sample-filename.txt]   | create a new file folder in a directory
| cp [sample-filename.txt] [sample-filename-copy.txt]   | copy file 
| cp -a [folder]/ [new_folder]   | copy folder with content
| mv [current-filename.txt] [new-filename.txt]   | move/rename file
| rm [sample-filename.txt]   | remove file
| rmdir [sample-dirname]   | remove directory
| ..  | navigate back two folders
| ../ ../  | nagivate back two levels (directories)
| ../[file folder]  | navigate back to [file folder]
| file  | obtain information about what type of file a file or directory is
| ~ (tilde)  | This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents

### Other useful terminology:

* _**Relative path** - A file or directory location relative to where we currently are in the file system.
* _**Absolute path** - A file or directory location in relation to the root of the file system.
