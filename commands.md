#Git Commands Cheat Sheet

1. Directory Navigation and Setup
List files in directory: ls
Change directory: cd <directory_name>
Show current directory path: pwd
Create a new directory: mkdir <directory_name>
Initialize a new Git repository: git init

2. File Operations
Create a new file: touch <filename>
Edit a file: vim <filename>
Delete a file: rm <filename>
View file contents: cat <filename>

3. Git Configuration
Set global username: git config --global user.name "your_name"
Set global email: git config --global user.email "your_email@example.com"

4. Staging and Committing Changes
Add a file to staging area: git add <filename>
Add all files to staging area: git add .
Commit changes with a message: git commit -m "commit message"

5. Checking Repository Status
Check the status of files: git status
View commit history: git log
View commit history in one line: git log --oneline

6. Branching
Create a new branch: git checkout -b <branch_name>
Switch to an existing branch: git checkout <branch_name>
List all branches: git branch

7. Restoring and Removing Files
Remove a file from staging: git rm --cached <filename>
Restore a deleted file: git restore <filename>

8. Remote Repositories
Add a remote repository: git remote add origin <repository_url>
View remote repository URL: git remote -v
Clone a repository: git clone <repository_url>

9. Viewing Logs and History
View Git history: history
Clear command history: clear

10. Exiting
Exit the terminal: exit
