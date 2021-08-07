
# GitHub Classroom Intro

We are going to be using **GitHub Classroom** to manage homework assignments. It simplifies the task of distributing/collecting assignments. 

It will also give you lots of experience using **git** and **GitHub**, which are very useful skills, both for personal use, and one that employers require of new hires.

## Summary

GitHub Classroom allows instructors to create a set of repositories that are templates for assignments that they can then assign to students. For each assignment, GitHub Classroom will make a special URL link and the instructor will share it with the students in the class. 

When the student enters the link in a browser, GitHub will create a private repository, with a name that includes both the assignment name and the student's GitHub username. For example, *assignment-1-username*.  

**The assignment repository is created within the GitHub Classroom account for the class, not the student's private GitHub account.** This simplifies the workflow for working on assignments. Both the instructor and the student have access to the assignment repository.

### Starting the Assignment

1. instructor provides students with a link to start the assignment. 
2. each student pastes the URL in the browser
3. a new assignment repo is created for each student in the GitHub Classroom account
4. students  **[clones their assignment repository](./git-cloning-existing-repo.md)** to their local computer

### Working on the Assignment
1. student do some work
2. student  adds **(git add .)** files if necessary
3. student commits **(git commit -m[comment])** their changes
4. student pushes  **(git push)** the changes back to your remote repo on GitHub
5. you do some more work
6. return to step 2, if necessary

### Turning in Your Assignment
There is no special step necessary to turn in your assignment. Your instructor has access to the repository and can see when your last push took place.

Once the assignment due date has passed, the instructor will review your work on GitHub, or clone the repository to their local computer so they can review and give feedback.


### Assignment Walkthrough

For this walkthrough, we will use a sample class with the name **intro-web-dev-fall-2021** and a sample assignment named **bash-shell**. You should substitute the appropriate names for your specific class.

You will receive a link (URL) to the assignment on the Homework page. Paste the link into a browser. You will be presented with a page like the following. 

Click the **Accept this assignment** button.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-1.png)

You will be directed to the following screen, asking you to wait for the assignment repository to be configured..

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-2.png)

After a minute or so, refresh the page and then click on the link to the assignment.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-3.png)

Clicking on the assignment link will redirect you to the GitHub website where a repository has been created for you. The repository is not within your own GitHub account. It is part of the classroom account for the course.

Notice the name of the repository: assignmentname-username. This allows the instructor to easily find assignments for each student.

![](https://raw.githubusercontent.com/hoc-labs/images/main/assignments-intro-4.png)
<br/>

**Clone the repository**. This create a copy of the repository on your local computer. Follow the directions in this [reference](./git-github-intro.md) on cloning.


**Assignment Contents**

The assignment repository contains all of the files you need to complete the assignment. 

* **README file** - The assignment will always contain at a minimum, a README file, which is what a repo displays as the default file for the repo. It is written in a special language, called [Markdown](https://guides.github.com/features/mastering-markdown/), which allows the author to add special tags which will format the content to display nicely.
* **Starter Files** - Depending on the nature of the assignment, there may be starter files included in the assignment repo that you will use to start your assignment. The README file will explain what is included and how to setup the assignment with any starter files.

**Turning in Your Assignment**

When you are satisfied with your assignment, do one final push to the GitHub repo. 

After you've completed these steps, your assignment has been turned in and your instructor can view your assignment and provide feedback if necessary.


**Note:** if you have forgotten the URL for the GitHub assignment repo, you can just paste in the assignment URL again and it will take you to the GitHub assignment repo page.

