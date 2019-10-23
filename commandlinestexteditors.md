** INSTRUCTIONS **

Go through these resources, and create a page in your Learning Journal repo that summarizes what learned 
as though you were presenting the material to *a non-technical friend* interested in learning about it.

Journal entry ideas:
Blog Article (2-3 paragraphs with code sample)
Dictionary / Flash Cards
Notes in outline form
Comparison of “basic” text editor vs coding-specific text editor vs IDE.

Document in your journal the different classifications of text editors, and 
why it’s important for software developers to be thoughtful about their selection of what they use to write code.
Record in your journal a “cheat sheet” or other resource for basic terminal usage.
______________________________________________________________

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

## "Basic” Text Editor vs Coding-Specific Text Editor vs IDE

It is important to choose the most appropriate tool for a job, and for developer sometimes this means making a decision between using an integrated development environment (IDE) or a text editor.

A text editor only does as its name describes and allows writing and making changes to plsin text. Once a developer creates code in a text editor, they can then input the content into command-line windows.  

In contrast, an IDE is a more sophisticated software that has complementing features meant to help web developers accomplish tasks with higher productivity, such as compilers, debuggers, static analyzers, contextual code completions ( which means you don’t have to type the entire line and save time), project navigation/overviews, etc. 

_(Note: A GUI is a system of interactive components such as icons and other graphical objects that help a user interact with computer software, such as an operating system. Familiar examples of GUI operating systems are Microsoft Windows, Apple System 7 and macOS and Chrome OS.)

The right tool will depend on a number of factors and below is a basic list of pros and cons for each tool. 

| Text Editor     | IDE  |
| ------------- | -------|
|   | Better suited for extensive development projects  |
| ls   | Supports unconscious competence and speeds up workflow, thanks to built-in shortcuts |
| Allows you to practice solely writing code and become more adept at the skill  | 
| Most computers already come with a pre-installed text editor, e.g. MAC has TextEdit and Windows has Notepad | Requires a system install |
|   | Often required if you are working with proprietary tooling (eg. Visual Studio)
| Downloads quickly and requires less memory  | Requires more memory than text editors


If the built-in text editor falls short in fulfilling your needs, then simply research the options for IDEs that work with your operating system.

At the end of the day, the best solution for you is one that matches the scope of the job and makes you feel at ease while diving into the work. However, as a developer the choice of using an editor or IDE is an important one and it should not be a one-time decision.  You should always be re-evaluating your choices and making changes wherever needed as new software is being created all the time and current software is always being updates, so you could be missing out on awesome new features if you limit yourself to only one tool.

Since most computers already come with a pre-installed text editor, e.g. MAC has TextEdit and Windows has Notepad.  You can use Notepad on a Windows machine or TextEdit on a Mac to immediately try out a text editor. If you find it falls short by not fulfilling your needs, it’s then simple to research the options for IDEs that work with your operating system.


As a programmer, the choice of editor/IDE is an important one, and it should not be a one-time decision. You should always be re-evaluating your choice and making changes wherever needed. In fact, it can be helpful to drop your favorite tool for a while and pick up a new one. The worst thing you can do is to pigeonhole yourself into a particular tool or to be overly loyal to a particular tool. A diverse tool set is always a good thing.

Basic Text Editor is a very simple application that reads and writes text files. It is particularly suited if you want to handle files in different encodings and character sets.

Examples of these include Notepad++, Text Wrangler, BB Edit, Visual Studio Code, Atom, Brackets, and Sublime Text, and most of these are free!

Choosing a text editor is a very personal choice, and at the end of the day the best text editor for YOU 
is the one you enjoy working with the most.  However, don't stuck on using just one text editor (What happens to me is that
I’ll stick with one text editor for a while, only to find out that the
others have all been updated so radically that they have new and
exciting features.)
The text editor is one of the most essential tools used by a software developers and it is important that the developer be thoughtful about their
selection when writing code as...

What features should you look for in a text editor? I would say some
of the most important features are: 1.) code completion; 2.) syntax
highlighting; 3.) a nice variety of themes (to reduce eye strain and
fatigue); and 4.) the ability to choose from a healthy selection of
extensions available when you need them. 

Since these text editors already come on your computers, why should
you download yet another text editor that does essentially the same
thing as the text editor that you already have? There are other text
editors that have features that you may be interested in, like the ones
we discussed before. Usually, the text editors that come on your
computer don’t have many features to speak of. They’re the barest
bare bones text editors you’ll encounter.

Please make sure that when you use the text editor that comes on
your computer, that you’re creating code in a plain text editor. You
should not see options for making text bold, underlined, or italic.
Plain text has no formatting options. There is no need to bold,
underline or italicize code. If you can make your text bold, underlined
or italic, then you might need to change a setting somewhere. Please
make sure you’re coding in plain text.
Also, make sure that when you use the text editor that comes on your
computer, that you first create a folder on your computer somewhere
(maybe on your Desktop, for example) to store your entire website.
As you create new documents with the text editor that comes on your
computer, save those files in the appropriate folders or sub-folders
within the main website folder.

Also, please make sure that when you’re saving your file, that they
have the appropriate extension at the end of the file names. For
example, your main HTML file should be called, “index.html.” Your
CSS file should be called something like “style.css.” The filename isn’t
as important as the extension (the “.html” and the “.css”).

Third-Party Options
Ok, what about third-party options? Let’s talk about software like:
Notepad++, Text Wrangler, BB Edit, Visual Studio Code, Atom,
Brackets, and Sublime Text. These text editors can all be downloaded
and installed to your computer from their respective websites. Each
of these titles do have some if not all of the features that we talked
about earlier, and most of this software is absolutely free! They are
widely used in web development today

## **(Create table comparison)**

The Difference Between Text
Editors and IDEs
A text editor kind of gives away what it does in the title—it edits text.
It also manages text, and manages files. I love that name “text
wrangler” because in a way that’s what really a text editor does. It
wrangles your text together into something meaningful.
An IDE (Integrated Development Environment) is really a suite of
different software all coming together. An IDE is a text editor, a file
manager, a compiler, and a debugger all in one software package.
You can think about an IDE very much like Microsoft Outlook. If
you’ve ever used Microsoft Outlook, you would have quickly noticed
that it was an email client, a calendar, a task manager, a to-do list all
in one software package. Similar to how an IDE is an all-in-one
software package.


___________________


