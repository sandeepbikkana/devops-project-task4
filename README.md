# devops-project-task4

# devops-project-task4
This is a Git-based version-controlled DevOps project.

✅ Step-by-Step Instructions
Step 1: Initialize a Local Git Repository
Create a new folder for your project.

Open terminal (or Git Bash), navigate to that folder.

Run:

bash:
git init
Step 2: Create a Remote GitHub Repository
Go to GitHub.

Click New repository.

Name it (e.g., devops-project-task4), add a description.

Do not initialize with README (you’ll add your own).

Click Create repository.

Step 3: Connect Local Repo to GitHub
In your terminal:

bash

git remote add origin https://github.com/your-username/devops-project-task4.git
Step 4: Create a .gitignore File
In your project folder, create a .gitignore file.

Add standard content like:

gitignore
Copy
Edit
*.log
node_modules/
__pycache__/
.env
Step 5: Create a README.md
In your project folder, create a README.md.

Add:

markdown



## Branches

- `main`: Stable code
- `dev`: Development branch
- `feature/*`: New features

## Tools

- Git
- GitHub
Step 6: Add and Commit Initial Files
bash

git add .
git commit -m "Initial commit: add README and .gitignore"
Step 7: Push to GitHub
bash

git branch -M main
git push -u origin main
Step 8: Create Branches
bash

git checkout -b dev
git push -u origin dev

git checkout -b feature/first-feature
git push -u origin feature/first-feature
Step 9: Make Changes in Feature Branch
Edit a file or add a script.

Commit your changes:

bash

git add .
git commit -m "Added first feature"
Push:

bash

git push
Step 10: Create a Pull Request (PR) on GitHub
Go to GitHub repo.

Click Compare & pull request (from feature to dev).

Add description and create PR.

Merge PR once reviewed.

Step 11: Merge dev into main
Create another PR: dev → main.

Merge it after testing.

Step 12: Add a Tag
bash

git tag v1.0
git push origin v1.0
Step 13: Document Everything in Markdowngit status
