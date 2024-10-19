Git Commands

1. Basic File Operations
Change directory:
  cd git-for-devops/

List files in long format:
  ls -ll
  ls -a

Create or edit a file:
  vi zero.txt
  touch one.txt two.txt

Remove a file:
  rm zero.txt

2. Repository Initialization
Initialize a new Git repository:
  git init

4. Checking Repository Status
Check the status of your repository:
  git status

6. Staging Files
Stage all changes:
  git add .

Stage specific files:
  git add one.txt
  git add three.txt

5. Removing Files from Git
Remove a file from the working directory and Git:
  git rm two.txt

Remove a file from Git (but keep it locally):
  git rm --cached one.txt
  git rm --cached three.txt

6. Committing Changes
Commit staged changes with a message:
  git commit -m "adding files to git"
  git commit -m "deleting three.txt"
  git commit -m "adding from dev branch"

8. Restoring Files
Restore a file from the last commit:
  git restore two.txt
  git restore three.txt

10. Git Configuration
Set global username:
  git config --global user.name "ShaguftaGMohammed"

Set global email:
  git config --global user.email "mohammed.shagufta.2022@gmail.com"

9. Viewing Git History
View commit history:
  git log

11. Working with Branches
Create and switch to a new branch:
  git checkout -b dev

Switch between branches:
  git switch dev
  git switch master

View branches:
  git branch

11. Inspecting the Git Directory
List details of .git directory:
  ls -lart .git
  ls -lrt .git

13. Listing Tracked Files
List tracked files:
  git ls-files
