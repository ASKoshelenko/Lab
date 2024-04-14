# GIT Basics Homework

This repository is part of a Git basics homework assignment for mastering fundamental git operations including branching, merging, and rebasing. The primary goal is to get comfortable with managing different branches and merging them using both `merge` and `rebase` techniques.

## Repository Structure

- `task1 – git practice I`: A directory where all initial git experiments are conducted.
  - `readme.txt`: An initial file to practice commits.
  - `index.html`: An HTML file used to demonstrate changes across different branches.
  - `images/`: Directory containing image files.
  - `styles/`: Directory containing CSS files.

## Branches

- `master`: Main branch where final changes are merged.
- `develop`: Development branch that serves as an integration branch for features.
- `images`: Branch where image files are added.
- `styles`: Branch where style sheets are added.
- `images2`: Second iteration of image additions using rebase.
- `styles2`: Second iteration of style additions using rebase.

## Tasks

### Part 1
Setup and initial project configuration including git installation, SSH key setup, and basic git settings adjustment.

### Part 2
Detailed practice with git branches:
1. Creation of `develop`, `images`, and `styles` branches.
2. Merging these branches into `develop`.
3. Repeating the process using `rebase` with `images2` and `styles2`.

### Part 3
Exploration of git history and pushing all changes to the remote repository.

## How to Run

Clone the repository and navigate into each branch to see the specific changes:

```bash
git clone git@gitlab.com:epamdevops/git.git
git checkout main

____________________________________________________________________________________

# GIT Basics Homework II

In this part of the homework, we built upon the foundational skills acquired in the first GIT Basics homework. Here's a rundown of the tasks completed and the skills practiced:

## Main Tasks

1. Checked out the `develop` branch to start off.
2. Performed all tasks in a new folder named `task2 – git practice II`.
3. Created a file in the new folder and committed it to track the changes.
4. Created a new branch `first` for separate feature development.
5. Created another new branch `second` for additional isolated changes.
6. Made several commits to `develop`, adding and altering files.
7. Checked out the `first` branch and made approximately five commits, introducing various changes.
8. Checked out the `second` branch and made three commits, ensuring at least one commit included changes in more than one file.
9. Performed interactive rebasing on the `second` branch to modify the commit history on top of `develop`. This involved:
    - Splitting a single commit into two separate commits.
    - Altering the content and message of another commit.
10. Merged the `second` branch into `develop` using the fast-forward method.
11. Switched to the `first` branch for further interactive rebasing.
12. During interactive rebasing of the `first` branch on top of `develop`:
    - Squashed three commits into one.
    - Dropped one commit entirely.
13. Merged the `first` branch back into `develop`, ensuring a fast-forward merge.
14. Finalized the new features and changes by merging `develop` into the `master` branch.
15. Pushed all local branches to the remote repository.
16. Saved the output of the `git reflog` command externally with the filename "GIT_Basics_homework_II.txt".

## Additional Tasks

1. Created four new commits on the `master` branch, each with minor changes to an existing file.
2. Rolled back the changes by executing `git reset --hard HEAD~4`, effectively undoing the last four commits.
3. Restored the changes from the third commit using the `git reflog` and `git cherry-pick` commands, showcasing the ability to recover lost commits.

This homework served to deepen the understanding of git commands and branching strategies, especially the power of interactive rebasing and the ability to rewrite history for cleaner, more understandable commit logs.
