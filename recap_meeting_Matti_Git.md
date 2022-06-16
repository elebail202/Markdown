## Meeting with Matti on how using Git

### Usual commands on Git

#### BASICS

*git clone <URL>* : clone a repo on your local machine

*git touch test.txt* : create a new file on your current project

*git diff* : really useful to see the differences made between 2 files (the committed and the one not committed yet)

*git status* : shows the actual state of the current directory

*git add -u* : adding modified files / One can also uses *add .*

*git log* : lists the complete commit history of the current branch

*git log --pretty=oneline* : it shows the different commit messages (the beginning)

*git log --pretty=oneline --abbrev-commit* : shows the commit message abbreviated

*git commit -m* : commit the file 

*git ci -m* : abreviation of commit / Is it really working on Windows ?

*git commit* : opens a text editor where you can write a detailed commit message. Title of the commit (then ... to show that there are other things written) and then one empty line and you can continue writing. "write" and "exit".


<span style="color:red">some **This is Red Bold.** text</span>

**[color=#26B260] IMPORTANT [/color]** : **COMMIT MESSAGES** : avoid "fixed a new line", "changed a new line" : Always use the `present` and not the past "fix","add" (when applied this commit will...blablabla : think this in my head) for the header line

*git show <5 first characters of the first commit message>* : shows the entire commit message

*git vim* : opens the file with vim / but hard to use better to use *code file* : opens the file on vscode

*git push*: could be enough (not all the *origin main*) if there is enough information to connect the 2 repos

*git init* : initialize git repo

---

#### BRANCHES

BRANCHES : possibility to create branches that can be merged with the main branches later

![alt text]("branches.jpg")
 
*git branch* : shows the different branches in the repo

*git checkout -b "feature/add-new-feature"* : checkout and create a new branch called "feature"

*git checkout main* : we go back in the main branch

*git br* : shows the latest modifications + lastest commit

*git branch --delete experiment* : delete the branch experiment

*git merge feature* : merge feature to main

(Other way of merging is rebase : we move the whole branch to add it where we want)

