# -2400030391---SkillEndSemExam-
# Initialize local project and commit
git init
git add .
git commit -m "Initial commit"

# Add GitHub remote
git remote add origin https://github.com/your-username/your-repo.git

# Push to GitHub
git branch -M main
git push -u origin main

# Go back one folder and clone to verify
cd ..
git clone https://github.com/your-username/your-repo.git
