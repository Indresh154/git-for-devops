1. Initializing a Repository
Creates a new, empty Git repository in your current directory.
git init

2. Checking the Status of Files
Shows the status of tracked and untracked files, and changes that need to be committed.
git status

3. Adding Files to Staging Area
Adds specific files or all changes to the staging area for the next commit.
git add <filename>
git add . (Adds all changes)

4. Committing Changes
Records the changes in the repository with a descriptive message.
git commit -m "Your commit message"

5. Viewing Commit History
Displays a log of all the commits made in the repository.
git log

6. Removing Files
Deletes files from the repository and stages the removal.
git rm <filename>

7. Restoring Files
Restores files to a previous state or undoes changes in the working directory.
git restore <filename>

8. Cloning a Repository
Creates a local copy of a remote repository.
git clone <repository_url>

9. Creating a Branch
Creates a new branch from the current branch.
git branch <branch_name>

10. Switching to a Branch
Changes the current working branch to the specified branch.
git checkout <branch_name>

11. Merging Branches
Merges changes from one branch into the current branch.
git merge <branch_name>

12. Deleting a Branch
Deletes the specified branch.
git branch -d <branch_name>

13. Pushing Changes to Remote Repository
Uploads local branch commits to the remote repository.
git push origin <branch_name>

14. Pulling Changes from Remote Repository
Fetches and merges changes from the remote branch to your current branch.
git pull origin <branch_name>

15. Setting Up Remote Repository
Links the local repository to a remote repository.
git remote add origin <repository_url>
