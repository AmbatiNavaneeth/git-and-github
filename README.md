# 🚀 Complete Git & GitHub Notes

1. Git Configuration

`git --version` → Shows installed Git version  

`git config --global user.name "Your Name"` → Sets username for commits  

`git config --global user.email "your@email.com"` → Sets email for commits  

`git config --list` → Displays all Git configuration settings  

## 🔹 2. Repository Setup

`git init` → Creates a new local Git repository  

`git clone <repository_url>` → Copies an existing remote repository to your local machine  

Example:  
`git clone https://github.com/username/project.git` → Downloads full project with commit history  

3. Basic Workflow

`git status` → Shows modified, staged, and untracked files  

`git add filename` → Adds specific file to staging area  

`git add .` → Adds all files to staging area  

`git commit -m "message"` → Saves staged changes permanently  

`git log` → Shows detailed commit history  

`git log --oneline` → Shows short commit history  

`git diff` → Shows unstaged changes  

`git diff --staged` → Shows staged changes before commit  

## 🔹 4. Branching

`git branch` → Lists all branches  

`git branch branch_name` → Creates a new branch  

`git switch branch_name` → Switches to another branch  

`git switch -c branch_name` → Creates and switches to branch  

`git branch -d branch_name` → Deletes a branch safely  

5. Merging

`git merge branch_name` → Combines another branch into current branch  

6. Remote Repository (GitHub)

`git remote add origin <repo_url>` → Connects local repo to GitHub  

`git remote -v` → Shows connected remote URLs  

`git push -u origin main` → Pushes code to GitHub for first time  

`git push` → Uploads new commits  

`git pull` → Downloads and merges latest changes  

`git fetch` → Downloads changes without merging  

7. Undo & Reset

`git restore --staged filename` → Removes file from staging area  

`git reset --soft HEAD~1` → Removes last commit but keeps changes  

`git reset --hard HEAD~1` → Deletes last commit and changes completely  

8. Stashing

`git stash` → Temporarily saves uncommitted changes  

`git stash list` → Shows saved stashes  

`git stash pop` → Restores last saved changes  

9. Tags

`git tag v1.0` → Creates a version tag  

`git push origin v1.0` → Pushes tag to GitHub  

10. Advanced Commands

`git rebase branch_name` → Reapplies commits on top of another branch  

`git reflog` → Shows full reference history  

`git blame filename` → Shows who modified each line in a file  

✅ Learning Outcome
- Understood Version Control System  
- Practiced Real Developer Workflow  
- Worked with Branching & Merging  
- Connected Local Repo to GitHub  
- Managed Commit History & Recovery  
