Assignment 1.5 — GitHub Essentials II

Aim

To upload a local project to GitHub and learn how to connect a local repository to a remote repository using Git commands.

1. Create a GitHub Account
Visit https://github.com/ and create a new account or sign in to an existing account.
2. Create a New Public Repository
Log in to GitHub.
Click the New Repository option.
Enter the repository name: web-development-practice.
Select Public.
Click Create Repository.
3. Connect the Local Repository to GitHub
Open the terminal in the local project folder and run:
git remote add origin https://github.com/YOUR-USERNAME/web-development-practice.git
git branch -M main

Replace YOUR-USERNAME with your GitHub username.
4. Upload the Project Using Git Push
Add and commit the project files:
git add .
git commit -m "Add initial project files"

Upload the files to GitHub:
git push -u origin main

5. Add a New File and Push the Second Commit
Create a new file named about.html and add the following code:


Save the file and run:
git add about.html
git commit -m "Add about page"
git push origin main

6. Verify Commit History on GitHub

1. Open the public repository on GitHub.
2. Check that the project files are visible.
3. Click the commit history link to view the commits.
4. Verify that both commits are displayed.


7. Public GitHub Repository Link
Repository URL:
https://github.com/YOUR-USERNAME/web-development-practice
