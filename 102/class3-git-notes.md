# Git Intro Notes


## Git

* is a dvcs (distributed version control system)
* synchronizes files with remote repositories - reduces rist of data loss
* allows to track file revisions, shows a change history
* lets multiple people to work on the same code - makes collaboration possible

## Creating Git Repository on my PC

### Steps

1. Copy the link from the green button in GitHub
2. Paste it into the terminal where you want the git folder to live
3. Use 'git clone LINK' command
4. Check it works: go into the new git folder and use command 'git remote -v', it returns 2 files _fetch_ and _push_
5. git status
6. 'git add .' (commits all changes in terminal)
7. A.C.P process: 
    * a for add changed files in terminal(git add . | git status) 
    * c for commit (git commit -m "WHY") where -m is a flag and stands for Add Message
    * p is push (git push origin main)

## More Commands
* git pull origin main - pulls changes from GitHub into your PC

[Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

[Back to home](../README.md)