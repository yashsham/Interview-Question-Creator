# Interview-Question-Creator

# Step 1: Create a new conda environment
conda create -n interview python=3.10 -y

# Step 2: Activate the environment
conda activate interview

# Step 3: Install all required Python packages
pip install -r requirements.txt

# --------------------------
# GitHub Setup Instructions
# --------------------------

# Step 4: Initialize git (if not already initialized)
git init

# Step 5: Add remote repository (replace with your actual repo URL)
git remote add origin https://github.com/your-username/interview-question-creator.git

# Step 6: Add all files to staging
git add .

# Step 7: Commit the changes with a message
git commit -m "Initial commit - added setup and requirements"

# Step 8: Set the default branch (optional but safe)
git branch -M main

# Step 9: Push code to GitHub
git push origin main
