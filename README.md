# Git Commands

---

To connect Project to github:-
Go to project folder -> Right click -> git bash here ->
Step 1: Initialize Git (if not already done):   git init
Check status:  git status
Step 2: Create a main branch (This creates and switches to a branch named main):   git checkout -b main
Step 3: Add your project files:   git add *
Step 4: Commit your changes:   git commit -m "Initial commit"
For the 1st time:  
git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

Step 5: Add the remote GitHub repo:    
git remote add origin https://github.com/your-username/your-repo.git

if want to Push code to master branch:   git push -u origin master 
Step 6: Push to main branch:   git push -u origin main
Step7: optionally delete the master branch:   git push origin --delete master
If got error:    git push -u origin main –force

---

## Steps to Push Changes to main Branch:
1.	Check your current branch:   git branch
2.	Make sure you're on the main branch. If not, switch:   git checkout main
3.	Check which files have changed:    git status
4.	Stage the changed files:   git add *  
Or only specific files:   git add README.md

5.	Commit your changes:   git commit -m "Updated service file"
6.	Before pushing your local code to GitHub:    git pull origin main --rebase
7.	Push to the remote main branch:   git push origin main
Or :    git push -u origin main –force

