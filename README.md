# Useful Git Commands

<h1>Git Version</h1>
git --version <br>

<h1>Configuring Git</h1>
git config --global user.name "username" <br>
git config --global user.email "email" <br>
git config --list <br>

<h1>Cloning</h1>
git clone <-- link --> <br>

<h1>Checking Status</h1>
git status <br>

<h1>Git command to configure a folder as a git repository</h1>
git init <br>

<h1>Add / Commit / Push</h1>
git add . (-- to add all the changes --) <br>
git add <-- filename --> (-- to change particular file --) <br>
git status <br><br>

git commit -m "comments" <br>
git status <br><br>

git push origin main (-- to push to main branch --) <br>
git status <br>

<h1>From Local Repository to Remote Repository</h1>
git remote add origin <-- link --> <br>
git remote -v (-- to verify remote --) <br>

<h1>Branch</h1>
git branch (-- list the branch/check the branch --) <br>
git branch -b <-- new branch name --> (-- create new branch --) <br>
git checkout <-- branch name --> (-- change to another brnach --) <br>
git branch -d <-- branch name --> (-- delete branch --) <br>
git branch -M <-- branch name --> (-- rename branch --) <br>

<h1>Diff / Merge</h1>
git diff <-- branch name --> (-- to differentiate between two branches sitting in one branch --) <br><br>

git merge <-- branch name --> (-- to merge with another branch --) <br>

<h1>Logs</h1>
git log

<h1>Undoing Changes</h1>
<b>Staged Changes</b> <br>
git reset <-- filename --> <br>
OR <br>
git reset <br><br>

</b>Commited Changes (for one commit)</b> <br>
git reset HEAD~1 <br><br>

</b>Commited Changes (for many commits)</b> <br>
git reset <-- commit hash --> <br>
git reset HARD <-- commit hash --> <br> 
git log (-- to find commit hash --) <br>



