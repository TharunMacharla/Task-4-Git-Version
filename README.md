Devops-pipeline-project
✅ Step 1: Setup and Initialization

Create a GitHub Repository

Go to GitHub.https://github.com/TharunMacharla/Task-4-Git-Version.git

Click on New Repository.

Name your project 

Add a description.

Select Public or Private.

Do not initialize with README.

Click Create Repository.

Clone Repository Locally git clone https://github.com/TharunMacharla/Task-4-Git-Version.git cd devops-pipeline-project

Initialize Git git init

✅ Step 2: Create and Setup Branches

Create and Switch to dev Branch git checkout -b dev

Create feature Branch from dev git checkout -b feature/setup-pipeline You can later make more feature branches like feature/docker-setup, feature/ci-cd, etc.

✅ Step 3: Add .gitignore and README

Add .gitignore Create a file named .gitignore and add common ignores: *.log *.env pycache/ node_modules/ dist/ .DS_Store

Add README.md Create README.md:

DevOps Pipeline Project
This project demonstrates DevOps CI/CD automation using version control best practices.

Branch Strategy
main – Stable production-ready code.
dev – Ongoing development.
feature/* – Individual features or tasks.
Tools Used
Git
GitHub Actions
Getting Started
Steps to clone and run the project locally...\

✅ Step 4: Make Commits

Track Changes and Commit git add . git commit -m "Initial commit: Added README and .gitignore"

Push to GitHub git push origin feature/setup-pipeline

✅ Step 5: Pull Request & Merge Create Pull Request

Go to GitHub.
Create a Pull Request from feature/setup-pipeline → dev.
Add description and task details.
Click Create Pull Request.
Merge to Dev After review, click Merge Pull Request → Confirm.

✅ Step 6: Merge to Main Once stable: git checkout main git pull origin main git merge dev git push origin main

✅ Step 7: Add Tags git tag -a v1.0 -m "Initial release" git push origin v1.0

![Screenshot 2025-04-11 165704](https://github.com/user-attachments/assets/34f92a87-9359-4cfd-9c87-0d289a22dc2a)

![Screenshot 2025-04-11 165714](https://github.com/user-attachments/assets/28e65f40-c907-41c6-af6b-842edf17d81c)

![Screenshot 2025-04-11 165724](https://github.com/user-attachments/assets/d451eede-6cae-4fdd-965f-bb2a41fef937)

![Screenshot 2025-04-11 165729](https://github.com/user-attachments/assets/e002efe8-f39c-4314-858e-303f59b4e3ce)


