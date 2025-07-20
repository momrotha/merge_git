## 📘 Command git
# Initialize a new Git repository
git init

# Add all files to staging
git add .

# Commit changes with a message
git commit -m "create: home page"

# (Optional) Check current remotes
git remote -v

# Push to the main branch (make sure the remote 'origin' is set)
git push origin main

# Check local and remote branches
git branch        # List local branches
git branch -r     # List remote branches

# Create and switch to a new branch named 'rotha'
git checkout -b rotha

# Add and commit changes on 'rotha' branch
git add .
git commit -m "update: changes on rotha branch"

# Push the new branch to remote
git push origin rotha

# Switch back to main branch
git checkout main

# Merge 'rotha' branch into 'main'
git merge rotha

# (Optional) If using Vim for merge message, type :wq to save and exit

# Push merged changes to main branch
git push origin main
