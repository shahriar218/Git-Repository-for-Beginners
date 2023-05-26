Definition: Git is a version control system of any type of files. 

Classification: (1)Local, (2)Remote
(1)Local: (a)Working Directory, (b)Stage, (c)Local Repository
(2)Remote: Github

Working Directory ----------> Stage, called the process 'add'
Stage ------------> Local Repository, called the process 'commit'

Git Commands:
-> mkdir Git_Repository_for_Beginners [Make a directory named Git_Repository_for_Beginners]
-> cd Git_Repository_for_Beginners [Enter into the directory]
-> touch README.md [Make a README.md file inside the directory]
-> cd ../ [Back to immediate directory, 1 step backword in directory]
-> clear [Clear the terminal]
-> git init [Initialize the git, as a result a .git folder generate]
-> git clone https://github.com/shahriar218/Git-Repository-for-Beginners.git [Make a clone of a remote(github) folder inside the local machine]
-> ls [List of all files of the current directory]

Two way for file-folder editing: (a)Pull repository from global, (b)Creating local repository, then initialize it
Staging definition: What things of files and folders are changes, need to stage

-> git status [Show the present condition of the directory, which file is staged, or not, which are untracked etc.]
-> pwd [Tell path of current directory]
-> git add --all or git add -A [Do stage all file-folder of the main directory]
-> git reset [All changes of files and folders back to in 'Working Directory' from 'Stage']
-> git add . [Do stage all changes from the current directory only]
-> git add * [Only deleted files changes information cann't staged but staged all others]
-> git add one.txt [Do individual file staged, for example, one.txt file]
