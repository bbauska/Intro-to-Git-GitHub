# Intro-to-Git-GitHub
Get started with Git and GitHub in this self-paced, introductory course! You’ll become familiar with collaborative version control and popular Git platforms. Collaboration and social coding are crucial parts of contemporary Software Engineering practices and the DevOps culture. 

You will begin this course with an overview of Git and Github fundamentals and explore key Git concepts such as branching and repositories, as well as the use of Git commands. 

You will also learn and practice various Git concepts such as forking, cloning and merging workflows using hands-on labs. 
And you’ll learn to use GitHub to work effectively as a team, and perform common Git operations, such as Pull Requests, from both the Web UI and command line. 

The course wraps up with a final project where you will start building your portfolio by creating and sharing a public/open-source GitHub project. 

By completing this course, you will demonstrate your Git and Github skills as well as add a project to your resume! 

All hands-on activities in this course can be performed using web-browser based tools and interfaces. Installation of any specialized software is NOT required on your own computer in order to complete the course.

## Syllabus
### Module 1 - Introduction to Version Control
In this Module (1), you'll be introduced to the concept of version control, which will make managing and rolling back your code look super easy. 

You’ll learn how to differentiate between files and the tools at your disposal to make this happen. 

Next, you'll be introduced to Git and how you can leverage that platform to improve your coding abilities. 

Once you’ve got a grasp on what Git is, you’ll install it and start using it to create and clone code repositories. 

Last up, you’ll deep dive into Git in order to get more familiar with the different tools and commands it has to offer.

  1.	Introduction to Module 1: Version Control
  2.	Keeping Historical Copies
  3.	Diffing Files
  4.	Applying Changes
  5.	Practical Application of Diff and Patch
  6.	Diff and Patch Cheat Sheet
  7.	What is Version Control and Automation
  8.	What is Git?
  9.	Installing Git
  10.	First Steps with Git
  11.	Tracking Files
  12.	The Basic Git Workflow
  13.	Anatomy of a Commit Message
  14.	Module 1 Wrap Up: Intro to Version Control

Summary: Qwiklabs Assessment: Introduction to Git

### Module 2 - Using Git Locally
In this module (2), you’ll dive into advanced Git interactions by skipping the staging area for small code changes, and understand how Git uses the HEAD alias to represent checked-out snapshots. 

Next, you’ll explore how to move and remove files before finally getting a cheat sheet to help you in your Git explorations! 
The next step of your learning will include how to undo changes before committing and how to amend commits once they’re submitted. 

Finally, you’ll be able to identify errors in commits that were submitted a while back. 

In the final section of this module, you’ll explore the concept of branching and merging. You’ll learn what a branch is, how to create one, and how they work in harmony with you and your code. 

Once you’re comfortable with branching, you’ll dive into merging, how it works with branched data, and how to deal with merge conflicts.

  1.	Intro to Module 2: Using Git Locally
  2.	Skipping the Staging Area
  3.	Getting More Information About Our Changes
  4.	Deleting and Renaming Files
  5.	Advanced Git Cheat Sheet
  6.	Undoing Changes Before Committing
  7.	Amending Commits
  8.	Rollbacks
  9.	Identifying a Commit
  10.	Git Revert Cheat Sheet
  11.	What is a branch?
  12.	Creating & Working with Branches
  13.	Merging & Merge Conflicts
  14.	Module 2 Wrap Up: Using Git Locally

Summary: Qwiklabs Assessment: Merging Branches in Git

### Module 3 - Working with Remotes
In this module (3), you’ll be introduced to GitHub and learn how it works with Git.

You’ll create new repositories and clone those repositories onto your computer. 

Next, we’ll explain what a remote repository is, how we can work with them, and how we can host them. 

You’ll get familiar with commands like modify, stage, and commit, which will be used for local changes, as well as the fetch command, which can pull any changes from remote repositories. 

Our final lesson will focus on learning about conflicts. This will allow you to explore the concepts of pull-merge-push workflows, pushing remote branches and rebasing your changes.

  1.	Intro to Module 3: Working with Remotes
  2.	What is GitHub?
  3.	Basic Interaction with GitHub
  4.	What is a remote?
  5.	Working with Remotes
  6.	Fetching New Changes
  7.	Updating the Local Repository
  8.	The Pull-Merge-Push Workflow
  9.	Pushing Remote Branches
  10.	Rebasing Your Changes with Examples
  11.	Best Practices for Collaboration
  12.	Creating a Personal Access Token in GitHub
  13.	Module 3 Wrap Up: Working with Remotes

Summary: Qwiklabs Assessment: Introduction to Github

### Module 4 - Collaboration
In this module (4), you’ll continue to explore the collaboration tools available in Git. 

You’ll learn about the tools that are available to help improve the quality of your code and to better track your code. This includes an overview of pull requests and how the typical workflow of a pull request looks like on GitHub. 

Next, you’ll dive into how you can squash changes in your code. 

We’ll finish up by providing you with a cheat sheet on fork and pull requests.

Next up, we’ll cover what code reviews are and what the code review workflow looks like. 

Then, you’ll learn about how to use code reviews on GitHub. 

The final lesson of this module will focus on managing projects. We’ll take a rundown of best practices on managing projects and how to manage collaboration within those projects. 

We’ll explore different ways of tracking issues and finish up by discussing the concept of continuous integration with your projects.

  1.	Intro to Module 4: Collaboration
  2.	A Simple Pull Request on GitHub
  3.	The Typical Pull Request Workflow on GitHub
  4.	Updating an Existing Pull Request
  5.	Squashing Changes
  6.	Git Fork and Pull Request Cheat Sheet
  7.	What are code reviews?
  8.	The Code Review Workflow
  9.	Managing Collaboration
  10.	Tracking Issues
  11.	Continuous Integration (CI)
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
## Module 1 – Introduction to Version Control
In module 1 you'll be introduced to the concept of version control, which will make managing and rolling back your code look super easy. You’ll learn how to differentiate between files and the tools at your disposal to make this happen. 

Next, you'll be introduced to Git and how you can leverage that platform to improve your coding abilities.  Once you’ve got a grasp on what Git is, you’ll install it and start using it to create and clone code repositories. 

Last up, you’ll deep dive into Git in order to get more familiar with the different tools and commands it has to offer.

### Learning Objectives
  •	Describe the concept of version control and why it is important to use
  •	Utilize the diff and patch commands to automate differentiating and editing files
  •	Explain what Git is and its benefits of use
  •	Install Git on local machine
  •	Utilize Git to create and clone repositories, add code, check the status of code, and commit code

#### Module 1-01. Course Introduction & Welcome
You've heard us talk a lot about programming and automation. This course focuses on a slightly different aspect. How to keep track of the different versions of your code and configuration files using version control systems or VCS. 

These are tools that everyone in IT can benefit from, even if it's not just for programming or automation itself. It will allow us to easily roll back when mistakes happen and also help us collaborate with others. 

You might have already heard of version control systems in the context of managing configuration files or maintaining the source code of programs and scripts. 

In this course, we'll introduce you to a popular VCS called Git, and show you some of the ways you can use it. We'll also go through how to set up an account with the service called GitHub, so that you can create your very own remote repositories to store your code and configuration. 

By the end of this course, you'll be able to store your codes history in Git, and collaborate with others in GitHub, where you'll also start creating your own portfolio. 

Nowadays, lots of employers were asked to see your GitHub portfolio when you're interviewing for IT roles. GitHub portfolios give companies an idea of what projects you've worked on and what kind of code you can write. This course will help you get one setup.

To ensure our project is a success, my team creates a narrative, figures out all the stake holders, and makes sure everyone is on the same page. After all of that comes the hardest part, executing the project to completion. To do that, it's essential we have a version control system, where each developer can store and share the code they create. This lets us track different revisions, rollback problematic changes, and work together effectively. 

Throughout this course, you'll learn about Git's core functionality, so you can understand how and why it's used in organizations. We'll look at both basic and more advanced features, like branching and merging. We'll demonstrate how having a working knowledge of a VCS like Git can be a lifesaver in emergency situations or when debugging, and we'll explore how to use a VCS to work with others through remote repositories, like the ones provided by GitHub. To do all this, and so you can follow along with the exercises in these modules, you'll need to install Git on your computer. This will also let you interact with GitHub, and upload your code there. 

For the examples in this course, we'll show a bunch of different Python scripts. While you don't need to know any Python to use Git, we do recommend that you have a basic knowledge of the language, so that you can understand the examples and the functionality we'll be demonstrating. If you've done the courses on Python in this program, you're covered. If you haven't, that's okay. But you might need to freshen up your Python skills to follow some of our examples. Also, since all the scripts will use Python 3, you'll need to have Python 3 installed in your computer to run them. 

For our examples, we're going to use a Linux computer, interacting with the Linux command line through the most common command line tools. Again, if you joined us for the Python courses, you're already familiar with all these concepts. If you're jumping into this program with this course, you might benefit from reviewing some of the most basic Linux commands. 

Please remember, some of these topics and modules are a little complex, so they might not 100 percent sink in the first time around. That's totally natural. Take your time, and review any content that's not completely clear. You'll get the hang of it eventually. Also, don't forget that you can use the discussion forums to connect with your fellow learners and ask questions anytime you need. All right. Ready to get started learning about Git and version control. Let's get to it.

### Module 1-02. Version Control/Keeping Historical Copies


