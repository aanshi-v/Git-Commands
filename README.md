# Git Commands

---


## Full Git Command Sequence (First Push)

#### Go to project folder -> Right click -> git bash here ->
### 1. Initialize a Git repository (if not already initialized)
git init

### 2. Check the current status of tracked/untracked files
git status

### 3. Create and switch to a new branch named 'main'
git checkout -b main

### 4. Add all project files to staging area
git add *

### 5. Commit your changes with a message
git commit -m "Initial commit"

### 6. Set global Git configuration (only once per machine)
git config --global user.name "Your Name" <br>
git config --global user.email "your.email@example.com"

### 7. Add remote GitHub repository (only once)
git remote add origin https://github.com/your-username/your-repo.git

### 8. Push code to GitHub and set upstream branch
git push -u origin main

### (Optional) 9. If push is rejected due to conflicts, force push (⚠️ Use with caution)
git push -u origin main --force


---


## Full Command Sequence (For Future Pushes)
1.  git branch
2.  git checkout main
3.  git status
4.  git add *
#### or stage a specific file
5.  git add README.md
6.  git commit -m "Your message"
7.  git pull origin main --rebase
8.  git push origin main

---

## Command Sequence (Push to a Custom Branch):
1. git init
2. git status
3. git checkout -b dev                 # Create and switch to new branch (e.g., 'dev')
4. git add *
5. git commit -m "Initial commit"
6. git remote add origin https://github.com/your-username/your-repo.git
7. git push -u origin dev              # Push to 'dev' branch

---

## Command Sequence (Steps to update your Git remote to the new GitHub repository:):
1. git remote -v
2. git remote set-url origin https://github.com/aanshi-v/new-repository-name.git
3. git push -u origin main







