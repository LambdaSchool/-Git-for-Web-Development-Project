## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
> Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

2. What is the difference between Git and GitHub?
> Git: A version control system used to track changes in files and coordinate work on those files among multiple people.
> GitHub: A hosting service for Git repositories that provides a web-based interface and additional collaboration and project management tools.

3. Why do we create a branch? 
> Creating a branch in GitHub (or in Git, generally) is an essential practice in software development for several reasons:

> Isolation of Work
> Branches allow developers to isolate their work from the main codebase (often referred to as the "main" or "master" branch). This means you can work on new features, bug fixes, or experiments without affecting the stable version of the project.

> Parallel Development
> Multiple developers can work on different features or fixes simultaneously without interfering with each other’s progress. Each developer can have their own branch, making collaboration more manageable and organized.

> Code Review and Collaboration
> Branches facilitate code review and collaboration. Developers can create a pull request (PR) from their branch to the main branch. This PR can then be reviewed, discussed, and approved by other team members before being merged. This process ensures that the code is thoroughly vetted before it becomes part of the main project.

> Testing and Validation
> Branches allow for thorough testing and validation of new code. You can deploy a branch to a testing environment to ensure everything works as expected without risking the stability of the main codebase.

> Version Control
> Branches provide a clear and organized history of changes. You can easily see what features were developed in which branches and when they were merged into the main codebase. This historical record is valuable for understanding the evolution of the project.

> Feature Development
> Developers often create branches for specific features. This practice is known as feature branching. It allows developers to work on a feature until it is complete and then merge it into the main branch, ensuring that only complete and stable features are added to the main codebase.

4. What is the purpose of a Pull Request?
> Pull requests are an essential tool for ensuring code quality, facilitating collaboration, and maintaining a clean and stable codebase in a collaborative development environment.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
> To switch between branches in Git, you use the git checkout or git switch command. Here's how you can switch from a branch named FIRSTNAME-LASTNAME to the main branch:

> Using git checkout
    > git checkout main
> Using git switch
    > git switch main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
> git fetch: Downloads changes from the remote repository but does not apply them to your working directory. It's useful for inspecting changes before merging.
> git merge: Combines changes from one branch into another. Used after fetching changes or when integrating different branches.
> git pull: Fetches and merges changes from a remote repository into your current branch in one step. It’s a shortcut for git fetch followed by git merge.

7. What is a merge conflict?
> A merge conflict occurs when Git cannot automatically reconcile differences between branches. To resolve a conflict, you must manually edit the conflicted files, remove conflict markers, and commit the resolved changes. Understanding how to handle merge conflicts is essential for collaborating on projects using Git.

8. How do you resolve a merge conflict?
> Attempting the merge and identifying conflicted files.
> Manually editing the files to resolve conflicts.
> Adding the resolved files to the staging area.
> Committing the merge to finalize the resolution.
