Here is a complete, step-by-step guide to successfully completing Assignment-1.5.md and preparing your required submission link.

Step 1: GitHub Account
Make sure you are logged into your GitHub account. If you don't have one yet, sign up for a free account.

Step 2: Create a New Public Repository
In the top-right corner of GitHub, click the + icon and select New repository.

Name your repository (e.g., git-assignment or match your local folder name).

Select Public.

Important: Leave "Add a README file", "Add .gitignore", and "Choose a license" unchecked (since you already have a local project initialized with commits).

Click Create repository.

Step 3: Connect Your Local Repository to the Remote Repository
Open your terminal inside your local project folder (the one you used in Assignment 1.4) and run the following commands to link it to GitHub. (Replace your-username and your-repo-name with your actual GitHub username and new repository name):

Set your default branch name to main (if it isn't already):

Bash
git branch -M main
Connect your local repository to the remote GitHub repository:

Bash
git remote add origin https://github.com/your-username/your-repo-name.git
Step 4: Upload Files Using git push
Push your existing local commits up to GitHub for the first time:

Bash
git push -u origin main
Step 5: Add a New File and Push the Second Commit
Create a new file in your project folder, for example, README.md or style.css.

Stage and commit this new file locally:

Bash
git add .
git commit -m "Add README file for project documentation"
Push this new commit up to GitHub:

Bash
git push
Step 6: Verify and Submit
Go to your public GitHub repository page in your browser.

Verify that all your files and your commit history show up correctly.

Submission: Copy the URL of your public repository from your browser's address bar to submit your assignment!