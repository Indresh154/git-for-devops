

Git Commands for DevOps

1. Setting up a Repository
Create a new directory
mkdir git-for-devops

Navigate into the directory
cd git-for-devops

Initialize a new Git repository
git init

2. File Management
Create new files
touch nibba.txt nibbi.txt hello-dosto.txt

Remove a file
rm hello-dosto.txt

View files in the directory
ls

View all files, including hidden files
ls -a

3. Checking the Status of Changes
Check the status of files in the repository
git status
4. Staging and Committing Changes
Add a specific file to the staging area
git add nibbi.txt

Add multiple files to the staging area
git add nibba.txt

Commit staged changes with a message
git commit -m "adding nibba nibbi"

View commit history
git log

5. Editing Files and Updating the Repository
Open a file in the editor (e.g., vim)
vim nibbi.txt

Add changes made in a file to the staging area
git add nibbi.txt

Commit changes with a new message
git commit -m "added new changes to nibbi"

6. Managing Branches
Create and switch to a new branch
git checkout -b dev

List all branches
git branch

Switch back to the master branch
git checkout master

Switch to an existing branch
git checkout dev

7. Undoing Changes
Restore a deleted file
git restore nibbi.txt
8. Cleaning and Navigation
Clear the terminal screen
clear

Change directory back to main directory
cd git-for-devops
