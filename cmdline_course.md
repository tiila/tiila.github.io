---
layout: default
---

Command-line course

Introduction

This is an introductory course to command-line utilities. The course introduces the basics of Unix command-line tools with examples of how to use them and benefit from them especially with language technology related tasks. During the course we learned how to navigate the Unix system and how to install, configure and run programs. Processing and managing files from the command-line through text file processing tasks is learned in the course.
Additionally, the course works as a starting point for creating ones own programs as it covers the mains points of version control with git and using Github as a platform for one's projects.


(for the final week, you can talk about Jekyll and Gihub Pages).  You should briefly describe the main content of each week and also briefly reflect on what you learned during the week (maybe 1-3 sentences for reflection). 
You need to include at least one list, image and table on the cmdline_course page. 

Read about formatting code in markdown. Every section should include some formatted example code or commands like:



Each section should have some formatted code or commands and an explanation.
You should include at least one table, list and image on your cmdline_course.html page.
Your markdown code should be neatly formatted.


## Week 1: Introduction to Command-Line Environments

The first week was about getting started with Unix and command-line basics as well as working with files from the command line.
The week covered installing Ubuntu on Windows and understanding the basics of the Unix operating system. During this week we learned how to create and edit files with the Nano text editor and move files between Ubuntu and Windows. Different file formats were also covered. 

Commands:

- **cp** copy
- **mv** move or rename
- **rm** delete
- **mkdir** make directory
- **cd** change directory and 
- **ls** list files and directories in a directory
- **pwd** print working directory
- **wget** install files/programs from web using url
- **cat** concatenate files
- **less** view the whole text file

**Reflection:** *I was new to Unix but found it relatively easy to get started even though having mainly used graphical interfaces it took some time to get comfortable using the command-line. The biggest challenge of the first week was installing Ubuntu on Windows as I had to reinstall Windows10 which took a good while and I ended up finishing the first week with Taito and Cubbli.*


## Week 2: Navigating a UNIX System

The second week introduced us new commands and how to manage user permissions for files and work as the root user. In this week we also learned how to copy and transfer files using the secure file transfer protocol. 

**Commands:**

- **su** switch user
- **sudo** su switch user to root
- **chmod** change permissions
- **ssh** connect to remote server
- **sftp** secure file transfer protocol

**Reflection:** *This week's tasks were very straightforward and simple to execute. I had used Taito before but I feel this course week still gave me some better understanding of how to work with remote servers.*


## Week 3: Corpus Processing

The third week was all about corpus and text file processing, how to handle errors and how to use regular expressions.

**Commands:**

- **head** show the beginning of a file
- **tail** show the end of a file
- **sort** sort alphabetically
- **wc** word count
- **uniq** show only uniq lines
- **sed** stream editor, stream changes in a file without opening
- **grep** search for a regular expression and print what is found

**Reflection:** *I found and still find managing huge text files from the command-line a bit difficult. Especially editing files with nano feel at least a bit clumsy. I was familiar with regular expressions already and enjoy creating them but it is difficult to accept not being sure whether the regular expression catches everything you want from a huge text file.*


## Week 4: Scripting and UNIX Configuration Files

Bash and Python ??? using commands in scripts 

- perl? 


**Commands:**

- **source .bashrc** executes the contents of the .bashrc file for example to update the changes made in the file
- **echo** 

**Reflection:** *This was probably the hardest week for me to fully understand everything that was covered. Environment variables, PATH variables and configuration files are in theory easy to understand, but when having to edit them I seem unable to find my own mistakes. Also knowing what I can and what I should not edit in configuration files can still be a mystery. *


##Week 5: Installing and Running Programs

During this week we took a deeper look on installations, environment variables, configuration files e.g. .bashrc and learn to look for hidden files with filenames starting with ".". 
We learned that successfull installations often require preinstalled libraries or other programs to work and that package managers such as apt for Unix and pip for Python are a useful too for handling these dependencies. The week provided some useful knowledge of how to work with Python, C and C++ programs on Unix. 

**Commands:**

- **make** builds other programs, libraries or other projects like corpus collections

**Reflection:** *This week was a very useful week for anybody needing to install different kinds of programs! I have installed many programs in the past and mostly succeeded after googling for help when the installations have been unsuccessfull at first. However, this week gave me some good tool for the future and made me actually understand some things I had already previously done.*


## Week 6: Version Control

Introduction to version control with Git.

**Commands:**

- **git init** initialize local repository
- **git add –A** add all the changes to the staging area
- **git status** get status of the added changes on the staging area to be committed
- **git commit –m** commit all changes to the repository with a message attached to the commit
- **git pull** pull the changes from remote repository to yourself
- **git push** push the committed changes to remote repository

**Reflection:**


## Final Assignment: Building Webpages using GitHub Pages

The rest of the course was committed to learning how to create GitHub Pages with Jekyll. This was done in the form of the final assignment where the task was to create one's own GitHub homepage using Jekyll. In the assingment the aim was to learn how to put up and edit the page and utilize Markdown for the content.

install + use

**Commands:** 

**Reflection:** *Setting up a page was not a very challenging task, but having to spend time on the content and for example creating an overleaf CV made the assignment very tedious. I would have also rather made some less identifiable content on my page but then found it easier and faster to use the facts of myself. I understand the final assignment works as a good revision of the course but I would have been happier, had I known at least to write the reflective parts after I had finished each week.*


