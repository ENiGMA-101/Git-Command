#############################################
# GitHub Repository Initialization Commands #
#############################################

# Step 1: Initialize a new Git repository
git init

# Step 2: Stage all files for commit
git add .

# Step 3: Commit the staged files with a message
git commit -m "init"

# Step 4: Rename default branch to 'main'
git branch -M main

# Step 5: Add your GitHub repository as a remote
# Replace <URL> with your actual GitHub repository URL
git remote add origin <URL>

# Step 6: Push the 'main' branch to GitHub
git push origin main

# Step 7 (Optional): Force push to override existing history
# Use with caution!
git push origin main --force
