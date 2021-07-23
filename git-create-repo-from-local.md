# Staring a new Repo from a Local Repo

You have a project on your local computer and now you want to also store the repository on GitHub.

In this scenario you need do the following:

### 1. Create a Local Git Repo
* **git init** - initialize your project folder to be a git repo.
* **git add .** - add all the files in your project to the staging area for the next commit.
* **git commit -m"your comments"** - commit your changes, creating a snapshot of project.
* **git branch -M main** - rename master to main

The command **git branch -M main** is necessary because git historically named the default branch "master" and they have migrated to naming the default branch **main**. 
### 2. Create a GitHub Repo
* create a repo on GitHub that will connect with your local repo.
* copy the URL for the new repo

### 3. Push Local Repo to GitHub
* **git remote add origin [GitHub repo URL]** - connect local repo with GitHub repo
* **git push -u origin main** - push changes to GitHub


The **git remote add origin [GitHub repo URL]** is connecting the local repository with the GitHub repository. The term **origin** is telling git what to call the remote GitHub repository. You could use any label you want, but **origin** is the convention. This label is necessary so that future commands, such as **push origin**, can tell git what remote GitHub repository the command is targeting.

