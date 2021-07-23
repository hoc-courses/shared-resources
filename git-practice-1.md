# Learning about git terminology through github


## Create a new git repo 

* log into github
* click + sign at top right and select new repo
* choose a name for this repo  (suggestion: git-practice-1)
* this repo can be public
  * check the the "Initialize with a README" checkbox
  * click the create repository button

## What you get with each repo

Once you have a repo in github, there are a number of things that come with the repo.  Notice the row of tabs at the top of the screen.  The first tab, named code, is essentially every file your repo tracks.  Currently there is a single README.md file that was created when you checked the box requesting one be automatically created.  The readme file is the default page displayed for a when you go to the code tab. It is a good idea to always create one so that visitors can get a summary of what the repo is for.

The tabs you will use most oftern are:

* code - files in repo
* issues - issue/bug tracking
* pull requests - merging branch changes into main branch
* wiki - allows you to build a wiki for your repo
* insights - analytics
* settings - managing repo settings, such as renaming and deleting the repo

A repo can help you organize a project, provide space for feedback, documentation, and some basic analytics.  For this first activity we will mostly just be using  the code tab.

For this lesson, we're going to focus on the code tab to work with the files in the repo.

## Commiting a new file
* Make sure you are in the code tab
* Click the add file dropdown and then the create new file button
* give the file the name "alphabet.txt"
* Edit the file by adding the following to it (notice the duplicate V)
```
ABCDEFG
HIJK
QRS
TUVV
WXYZ
```
* Click the commit new file button at the bottom.

This file is now known to git.  git is storing a version of this file

## Modify the file
* click the link for the file you created in the last step 
* hit the pencil icon in top right to edit the file
* remove the duplicate V
* then click commit changes button at the bottom.

## Lets look at the history
* click on the file in code tab
* click the history button (top right)
* notice there are two commits each has a 7 digit hex code associated.
* This 7 digit hexcode is actually the beginning of a much longer hex code that uniquely identifies each commit.
* click on the "Update alphabet.txt" link and notice you can see the changes made in that version.
* ```+``` and green indicate additions
* ```-``` and pink indicate deletions

## Now, from the command line

We are now going to repeat these steps, but instead of using the GitHub GUI, we're going ot issue the git commands from the CLI. That's because most of the time, you will use git commands from the command line within VS Code or a Git Bash shell. It's much faster to use the command line for frequent tasks.

## Clone the repo

Follow the steps in the following article.
[Cloning an existing repo](https://github.com/hoc-courses/shared-resources/blob/main/git-cloning-existing-repo.md)

Load the repo folder in VS Code and open a Terminal window so you have access to the CLI from within VS Code.

Type the command ````git status````
This checks if there are any 



