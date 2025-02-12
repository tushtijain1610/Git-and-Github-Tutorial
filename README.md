A beginner-friendly guide to understanding and using Git and GitHub for version control and collaboration.

1️⃣ Git: Version Control System
Git is a popular, free, open-source, fast, and scalable version control system that helps track changes in code.

Why Use Git?
✔ Track code history
✔ Collaborate with teams
✔ Revert to previous versions easily

2️⃣ GitHub: Code Hosting Platform
GitHub is a web-based platform that allows developers to store, manage, and collaborate on projects using Git.

🔹 Think of GitHub like a folder, but in GitHub terms, it's called a Repository (Repo).

3️⃣ README File
A README.md file contains essential project details:
📌 Project name
📌 How to use it
📌 Technologies used

4️⃣ Setting Up Git
Before using Git, configure it with your details:

🔹 Global Configuration (Applies to all repositories)

bash
Copy
Edit
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list  # View configuration
🔹 Local Configuration (For a specific repository)
Used when working with multiple accounts.

5️⃣ Cloning a Repository & Checking Status
Clone: Download a GitHub repository to your local machine.

bash
Copy
Edit
git clone <repo-link>
Status: Check the current state of your repository.

bash
Copy
Edit
git status
6️⃣ Essential Terminal Commands
Command	Description
cd <folder>	Change directory
clear	Clear terminal screen
ls	List all files/folders
ls -a	Show hidden files
7️⃣ Understanding File States in VS Code
M (Modified): File has changes that are not yet staged.
U (Untracked): New file not being tracked by Git.
Staged: File is ready to be committed.
Unmodified: No changes detected.
8️⃣ Tracking Changes: Add, Commit, Push
1️⃣ Add files to staging area

bash
Copy
Edit
git add <file-name>  # Add a specific file
git add .            # Add all files
2️⃣ Commit changes (save snapshot)

bash
Copy
Edit
git commit -m "Your commit message"
3️⃣ Push changes to GitHub

bash
Copy
Edit
git push origin main
9️⃣ Initializing a Git Repository
To create a new Git repository:

bash
Copy
Edit
git init  
git remote add origin <repo-link>  # Connect to remote repo
git remote -v  # Verify remote connection
git branch -M main  # Rename branch to main
git push origin main  # Push to GitHub
🔟 Git Workflow
GitHub Repo → Clone → Make Changes → Add → Commit → Push

1️⃣1️⃣ Working with Branches
1️⃣ Check current branches

bash
Copy
Edit
git branch
2️⃣ Switch to another branch

bash
Copy
Edit
git checkout <branch-name>
3️⃣ Create a new branch & switch

bash
Copy
Edit
git checkout -b <new-branch>
4️⃣ Delete a branch

bash
Copy
Edit
git branch -d <branch-name>
1️⃣2️⃣ Merging Code
Method 1: Git Commands
Compare branches before merging:

bash
Copy
Edit
git diff <branch-name>
Merge branches:

bash
Copy
Edit
git merge <branch-name>
Method 2: Pull Requests (PRs)
Create a PR on GitHub to merge branches.

1️⃣3️⃣ Syncing with Remote Repo
Pull latest changes from GitHub:

bash
Copy
Edit
git pull origin main
1️⃣4️⃣ Undoing Changes
Case 1: Unstage Changes
bash
Copy
Edit
git reset <file-name>
git reset
Case 2: Undo the Last Commit (Keep Changes)
bash
Copy
Edit
git reset HEAD~1
Case 3: Undo a Specific Commit
bash
Copy
Edit
git reset <commit-hash>
git reset --hard <commit-hash>  # Removes changes permanently
1️⃣5️⃣ Forking a Repository
A fork is a copy of another repository that allows you to make changes without affecting the original repo.

🔹 Use it to contribute to open-source projects!

🎯 Now you’re ready to use Git and GitHub effectively! 🚀
This guide helps you understand the fundamentals of Git and GitHub, from setup to collaboration. Happy coding! 😊
