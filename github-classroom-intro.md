
# GitHub Classroom Intro

We are going to be using **GitHub Classroom** to manage homework assignments. This will give you lots of experience using **git** and **GitHub**, which is a very useful skill, both for personal use, and one that employers require of new hires.

## Summary

GitHub Classroom allows instructors to create a set of repositories that are templates for assignments that they can then assign to students.

For each assignment, GitHub Classroom will make a special URL link. When you go to that link in a browser, GitHub will create a private repository for you, with a name that includes both the assignment name and your GitHub username.  This repository is a clone of the starter repository. The repository is a private repository owned by the course staff (so we can view it) that the student will have write access to.

The student uses this created repository to create their assignment. This will involve cloning the repository to your local computer, editing the files and adding new ones, committing the changes (to your local repository), and pushing these changes back to the GitHub repository (so the instructor can view it).

The basic workflow is:

* The instructor provides you with a repository on GitHub with the start of a project.
* You **clone** this repo to your laptop
* You do some work
* You **add** files if you created new ones in the project
* You **commit** your work
* You **push** the changes back to your remote repo on GitHub
* You do some more work
* repeat until done
* The instructor clones your repo from GitHub so they have a copy to look at.

## Starting an assignment

For this tutorial, we will use a sample class with the name **intro-web-dev-fall-2021** and a sample assignment named **bash-shell**. You should substitute the appropriate names for your specific class.

You will receive a link (URL) to the assignment on the Homework page. Paste the link into a browser. You will be presented with a page like the following. 

Click the **Accept this assignment** button.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-1.png)

You will be directed to the following screen, asking you to wait for the assignment repository to be configured..

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-2.png)

After a minute or so, refresh the page and then click on the link to the assignment.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-3.png)

Clicking on the assignment link will redirect you to the GitHub website where a repository has been created for you. The repository is not within your own GitHub account. It is part of the classroom account for the course.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-4.png)

### Assignment Contents

The assignment repository contains all of the files you need to complete the assignment. 

### README.md - Assignment Directions

The assignment will always contain at a minimum, a README.md file, which is what a repo displays as the default file for the repo. It is written in a special language \(markdown\) which allows the author to add special tags which will format the content to display nicely.

#### Starter Files

Depending on the nature of the assignment, there may be starter files included in the assignment repo that you will use to start your assignment. The README.md file would explain what is included and how to setup the assignment with any starter files.

### Cloning the Repository to your Local Computer

Follow the directions in this [reference](./git-github-intro.md) on cloning.



Once the command has completed, you can issue the **ls** command to see that a new directory, named bash-shell-[your-githubusername], has been created. Use the **cd** command to change directories into the newly created directory, followed by the **ls** command, to see the files that are included in this assignment.

## Turning in Your Assignment.

Once these operators are complete, your assignment has been turned in and your instructor can view your assignment and provide feedback if necessary.

At any time, you can return to the GitHub page for the assignment repo, and refresh the page to see any changes you have pushed.

**Note:** if you have forgotten the URL for the GitHub assignment repo, you can just paste in the assignment URL again and it will take you to the GitHub assignment repo page.

