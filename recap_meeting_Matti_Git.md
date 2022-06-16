## Meeting with Matti on how using Git

### Usual commands on Git

#### BASICS

<ins>*git clone <URL>*</ins> : clone a repo on your local machine

<ins>*git touch test.txt*</ins> : create a new file on your current project

<ins>*git diff*</ins> : really useful to see the differences made between 2 files (the committed and the one not committed yet)

<ins>*git status*</ins> : shows the actual state of the current directory

<ins>*git add -u*</ins> : adding modified files / One can also uses *add .*

<ins>*git log*</ins> : lists the complete commit history of the current branch

<ins>*git log --pretty=oneline*</ins> : it shows the different commit messages (the beginning)

<ins>*git log --pretty=oneline --abbrev-commit*</ins> : shows the commit message abbreviated

<ins>*git commit -m*</ins> : commit the file 

<ins>*git ci -m*</ins> : abreviation of commit / Is it really working on Windows ?

<ins>*git commit*</ins> : opens a text editor where you can write a detailed commit message. Title of the commit (then ... to show that there are other things written) and then one empty line and you can continue writing. "write" and "exit".

**IMPORTANT** : COMMIT MESSAGES : avoid "fixed a new line", "changed a new line" : Always use the `present` and not the past "fix","add" (when applied this commit will...blablabla : think this in my head) for the header line

<ins>*git show <5 first characters of the first commit message>*</ins> : shows the entire commit message

<ins>*git vim*</ins> : opens the file with vim / but hard to use better to use *code file* : opens the file on vscode

<ins>*git push*</ins> : could be enough (not all the *origin main*) if there is enough information to connect the 2 repos

<ins>*git init*</ins> : initialize git repo

---

#### BRANCHES

BRANCHES : possibility to create branches that can be merged with the main branches later

![alt text]("branches.png")
 
<ins>*git branch*</ins> : shows the different branches in the repo

<ins>*git checkout -b "feature/add-new-feature"*</ins> : checkout and create a new branch called "feature"

<ins>*git checkout main*</ins> : we go back in the main branch

<ins>*git br*</ins> : shows the latest modifications + lastest commit

<ins>*git branch --delete experiment*</ins> : delete the branch experiment

<ins>*git merge feature*</ins> : merge feature to main

(Other way of merging is rebase : we move the whole branch to add it where we want)

