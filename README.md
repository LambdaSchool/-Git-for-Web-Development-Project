# Git for Web Development Project
In this project you will be using the concepts learned in the Git for Web Development lesson to fork/clone/push/and submit a PR for each project during this sprint.

This project consists of two parts:

## Part One:
You will need to follow the Lambda School Git Workflow to add a file to this project follow the steps below:

- [ ] Create your own version of this repo - Fork
- [ ] Add your PM as a collaborator
- [ ] Clone this repo
- [ ] Create a branch `git checkout -b 'firstName-lastName'`
  - [ ] Add a file to the project called `yourFirstName-yourLastName`.txt. This file can contain anything.
  - [ ] Run your usual git commands for adding/commiting and pushing **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Part Two:
Go back and follow the same steps for your [UI-III-Flexbox project](https://github.com/LambdaSchool/UI-III-Flexbox) and your [User Interface - Great Idea Project](https://github.com/LambdaSchool/User-Interface).

In order to do this, you **do not** need to create new forks of these projects. Follow the steps below for each project:

- [ ] Add your PM as a collaborator to your fork. 
- [ ] Go into your project folder, make a new branch `firstname-lastname`
- [ ] Add your first and last name to the README.md file in the project and save.
- [ ] add/commit/and push to your own branch  **Be sure to push to your branch!**
- [ ] Create a Pull-Request to submit your work
  - [ ] Use your own student fork as the base (compare across forks, base-fork -> master).
  - [ ] Add your PM as a reviewer on the Pull-Request
- [ ] PM then will count the Assignment as done by merging the HW back into master "STUDENT FORK".

## Stretch
- [ ] While the processes learned here will set you up to be successful in most situations, they are just the tip of the iceberg in learning Git. Independantly research the following topics to learn more about Git.

  - [ ] Research and understand what a `merge conflict` is and how to resolve it.
  - [ ] Reseach the Git commands `pull`, `rebase`, `merge`. These commands will allow you to bring in changes that other developers push to the master branch.
  - [ ] Reseach the Git commands `reset `, `revert`, `clean`. These commands will allow you to go back and ammends previous commits you have made.

- [ ] Research and set up a Graphical User Interface (GUI) Git console. 

- [ ] Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push. 




# Stretch Answers  :smile:

- [ ] Research and understand merge conflict

* Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.

* [Competing line change merge conflicts](https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line#competing-line-change-merge-conflicts "Competing line change merge conflicts")

* [Removed file merge conflicts](https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line#removed-file-merge-conflicts "Removed file merge conflicts")

    -------------------------------------------------------------------------------------------

:flushed:
- [ ] Reseach the Git commands `pull`, `rebase`, `merge`.

* ***git-pull:*** - Fetch from and integrate with another repository or a local branch.
* SYNOPSIS:

``` git pull [<options>] [<repository> [<refspec>…​]] ```

* ***git-rebase*** - Reapply commits on top of another base tip.
* SYNOPSIS:

``` git rebase [-i | --interactive] [<options>] [--exec <cmd>] [--onto <newbase> ```
```     [<upstream> [<branch>]]```
``` git rebase [-i | --interactive] [<options>] [--exec <cmd>] [--onto <newbase>] ```
```     --root [<branch>] ```
``` git rebase --continue | --skip | --abort | --quit | --edit-todo | --show-current-patch ```


  --------------------------------------------------------------------------------------------

:flushed:
* ***git-merge*** - Join two or more development histories together.
* SYNOPSIS:

``` git merge [-n] [--stat] [--no-commit] [--squash] [--[no-]edit]```
```	[-s <strategy>] [-X <strategy-option>] [-S[<keyid>]]```
```	[--[no-]allow-unrelated-histories]```
```	[--[no-]rerere-autoupdate] [-m <msg>] [-F <file>] [<commit>…​]```
``` git merge --abort```
``` git merge --continue```



- [ ] Reseach the Git commands `reset `, `revert`, `clean`. :innocent:

* ***git-reset*** - Reset current HEAD to the specified state.
* * SYNOPSIS:

``` git reset [-q] [<tree-ish>] [--] <paths>…​```
``` git reset (--patch | -p) [<tree-ish>] [--] [<paths>…​]```
``` git reset [--soft | --mixed [-N] | --hard | --merge | --keep] [-q] [<commit>]```

* ***git-revert*** - Revert some existing commits.
* * SYNOPSIS:

``` git revert [--[no-]edit] [-n] [-m parent-number] [-s] [-S[<keyid>]] <commit>…​```
``` git revert --continue```
``` git revert --quit```
``` git revert --abort```

* ***git-clean*** - Remove untracked files from the working tree.
* SYNOPSIS:

``` git clean [-d] [-f] [-i] [-n] [-q] [-e <pattern>] [-x | -X] [--] <path>…​ ```



- [ ] Research and set up a Graphical User Interface (GUI) Git console. :scream:

* [Graphical User Interface (GUI) Git console](https://gitforwindows.org/ "Graphical User Interface (GUI) Git console")



- [ ] Research and setup SSH keys with Github, so that you do not need to input your username/password each time you push. :sunglasses:

* [Connecting to GitHub with SSH](https://help.github.com/en/articles/connecting-to-github-with-ssh "Connecting to GitHub with SSH")


:bowtie:

 ![picture alt](https://eralpkor.com/img/relaxing_norman.JPG "Norman")
