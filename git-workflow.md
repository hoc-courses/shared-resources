# Typical Git Workflow

The following depicts the process that occurs on your local computer and the commands involved with working with your local repository, and the push command that pushes the changes from your local repository to your corresponding GitHub repository.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-9.png)

**git init** - this step occurred automatically when the GitHub repository was cloned to your local computer. It creates a private directory, named .git, that stores all the information for Git to track your repo. You only need to do this step when you create a local repository first.

**git status** - returns a list of untracked (new) and modified files and tracked files (files in the staging area ready for the next commit).

**git add** - adds any changed files to the staging area to be committed to your local repository.

**git commit -m "some message"** - commits the changed files in your staging area to a new snapshot, which is permanently available in the history of tracked changes for your repo. This git commit command takes **an additional flag, -m**, **followed by a message in quotes**, to provide a message to describe the changes associated with this commit.

**git push** - pushes any changes you have made since the last commit to the GitHub repository, thereby syncs up the GitHub repo with your local repo.

These three steps, **a**dd, **c**ommit, **p**ush, are commonly referred to as the **ACP cycle**, and can be repeated as many times as desired as you work on your project. Is is a good practice to push to GitHub whenever you are at a stable point after making some changes. This ensures that you can always return to that point if the need arises.
<br/>


### Staging Area
One of the most confusing parts when you're first learning git is the concept of the staging environment and how it relates to a commit.

A commit is a record of what changes you have made since the last time you made a commit. Essentially, you make changes to your repo (for example, adding a file or modifying one) and then tell git to put those changes into a commit.

Commits make up the essence of your project and allow you to track the changes that have been made to the project over time. 

So, how do you tell git which files to put into a commit? This is where the staging environment or index come in.  When you make changes to your repo, git notices that a file has changed, but you must add new files to the staging area (the set of files that will be included in the next commit) for them to be included in the commit.

To add a file to a commit, you first need to add it to the staging environment. To do this, you can use the git add  command.
Once you've used the git add command to add all the files you want to the staging environment, you can then tell git to package them into a commit using the git commit command.



