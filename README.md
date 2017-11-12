# Crash Course Sample Project on Git

Tutorial on how Git and Github works.

## Overview
* Git is a version control system (VCS) for tracking changes in computer files
  * Created in 2005 - distributed version control (decentralized)
  * Coordinate with between multiple developers (local + remote repos)
* Concepts:
  * Keep track of code history (snapshots of files) - committing
* Recommended: git-scm.com
  * Use gitbash over standard command line
* Add a readme.md for public repositories


## Syntax
* $ git init - initialize local git repository
* $ git add <file>  - add file(s) to index/staging
* $ git rm --cached <file> - remove file(s) from index/staging
* $ git status - check status of working tree
* $ git commit - commit changes to index (local repository)
  * With commenting step:
    * After committing, press ‘i’ to start typing and ‘escape’ to exit
    * :wq - used to save the commit
  * Without commenting step:
    * $ git commit -m ‘comment’
* $ git branch <name> - creates a branch
* $ git checkout <branch> - switches to another branch
* $ git merge <branch> - merges branches
* $ git remote add origin <git url> - add a remote repository
* $ git push -u origin <branch> - push to remote repository (github/bitbucket)
  * $ git push - push new updates
* $ git pull - pull latest from remote repository
* $ git clone - clone repository to new directory
* $ git --version - show version number
* $ clear - clear previous entries 
* $ git config --global user.name|email ‘name’ - add name and email address to Git
* $ touch <file> - creates a file on the folder


## Additional Notes
* $ git add star.html - Adding star to filenames will use it as a wildcard and add all files to staging 
* $ git add . - To target all files, use a period (.)
* $ touch .gitignore - ignores files to avoid adding them to staging
  * Add the filename or directory name (/dir) to the gitignore to not include it
* Ctrl + shift + insert - copy and paste into gitbash

## Acknowledgments

* Tutorial Author: Traversy Media
* Tutorial Link: https://www.youtube.com/watch?v=SWYqp7iY_Tc