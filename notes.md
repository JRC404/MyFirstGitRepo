# Using Git for the first time, by Jacob Reilly-Cooper, an idiot

**Open up your terminal in the directory you have open**

* git status
    * fatal: not a git repository (or any of the parent directories): .git
    * We have not initialised git in the folder

* git init
    * Initialized empty Git repository in

* git status
    * We should now see something a little different - untracked files or No commits yet

* touch index.js
    * create the file index.js

* git status
    * index.js should show as an untracked file :-)

* To track it, we need to tell git to track it with a simple command:

* git add . OR git add index.js
    * git add . will track **ALL** files in the folder
    * git add index.js will only track index.js

