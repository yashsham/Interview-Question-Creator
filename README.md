# Interview-Question-Creator Setup and GitHub Push Guide

'''bash
# Step 1: Create a new conda environment named 'interview'
conda create -n interview python=3.10 -y

# Step 2: Activate the newly created environment
conda activate interview

# Step 3: Install all required packages from requirements.txt
pip install -r requirements.txt

# -------------------------------
# GitHub Commands for Deployment
# -------------------------------

# Step 4: Initialize a local Git repository (skip if already initialized)
git init

# Step 5: Add remote GitHub repository (replace with your actual GitHub repo URL)
git remote add origin https://github.com/your-username/interview-question-creator.git

# Step 6: Add all project files to Git staging
git add .

# Step 7: Commit the changes with a descriptive message
git commit -m "Initial commit - project setup complete"

# Step 8: (Optional) Rename the current branch to 'main'
git branch -M main

# Step 9: Push code to the GitHub repository
git push origin main
'''


# Step 7: Commit the changes with a message
git commit -m "Initial commit - added setup and requirements"

# Step 8: Set the default branch (optional but safe)
git branch -M main

# Step 9: Push code to GitHub
git push origin main
