## Meeting with Matti on how use Git

### Usual commands on Git

git add -u : adding modified files

git log : shows latest changes in the files

git ci -m : abreviation of commit

git status : shows the actual status

git diff : really useful to see the differences made between 2 commits

git commit : opens a text editor where you can write a detailed commit message. Title of the commit (then ... to show that there are other things written) and then one empty line and you can continue writing. "write" and "exit".

git log --pretty=oneline : it shows the different commit messages (the beginning)

git show <5 first characters of the first commi message> : shows the entire message

git vim : opens the file with vim / but hard to use better to

code file : opens the file on vscode

git log --pretty=oneline --abbrev-commit : shows the commit message abbreviated

IMPORTANT : COMMIT MESSAGES : avoid "fixed a new line", "changed a new line" : Always use the present and not the past "fix","add" (when applied this commit will...blablabla : think this in my head) for the header line

git push : could be enough if there is enough information to connect the 2 repos

git init : initialize git repo