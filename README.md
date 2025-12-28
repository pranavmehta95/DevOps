# Git Bash & GitHub Hands-On Project  
## Version Control Demonstration: Personal Portfolio Website

This project demonstrates hands-on usage of **Git and GitHub** through a simple **Personal Portfolio Website** built using **HTML and CSS**.  
The main goal of this repository is to practice and showcase **core version control concepts** rather than complex application logic.

This README is intentionally detailed (yes, long) so beginners can follow each step without confusion. All Git commands used during development are documented clearly.

---

## Overview

- Create a static personal portfolio website
- Initialize and manage a Git repository using macOS Terminal
- Perform at least **10 meaningful commits**
- Create and work with **multiple branches**
- Merge branches into the main branch
- Intentionally create and resolve a **merge conflict**
- Push the complete project to GitHub
- Document the entire workflow using Markdown

---

## Requirements

- macOS / Linux / Windows
- Git (installed and configured)
- GitHub account
- Terminal (macOS Terminal / Git Bash / VS Code Terminal)
- Any text editor (VS Code recommended)
- Basic knowledge of HTML and CSS

---

## Clone the Project

```bash
git clone https://github.com/pranavmehta95/DevOps
cd DevOps

Run the Project Locally

This is a static HTML/CSS project, so no server is required.

macOS / Linux

open index.html

git-portfolio-project/
│── index.html      # Main HTML file
│── style.css       # Styling file
│── README.md       # Project documentation

Git Repository Initialization

Initialize a local Git repository:
git init

Check repository status:
git status

Commit Workflow
All changes were committed using meaningful commit messages.
Example:
git add index.html
git commit -m "Initial HTML structure for portfolio"

git log --oneline
The repository contains 10+ commits documenting incremental changes.

Branching Strategy
The following branches were created and used during the project:
Branch Name                                   Purpose

feature/skills-section                     Add and improve skills section
test/responsive-check                      Test layout and responsiveness
bugfix/nav-link-fix                        Fix navigation issues
experiment/color-theme                     Experiment with a new color scheme



Create a branch:
git checkout -b feature/skills-section
List all branches:
git branch

Merging Branches
After completing work on a branch, changes were merged into the main branch.
git checkout main
git merge feature/skills-section
This workflow was followed for all feature, test, bugfix, and experiment branches.

Merge Conflict Demonstration
A merge conflict was intentionally created by editing the same section of README.md in two different branches.
During merge:
git merge test/responsive-check
Git reported a merge conflict.


Conflict Resolution Steps
	1.	Open the conflicted file
	2.	Identify conflict markers:
    <<<<<<<
    =======
    >>>>>>>

    3.	Manually resolve the conflict
	4.	Save the file
	5.	Commit the resolved changes
git add README.md
git commit -m "Resolved merge conflict in README"
This confirms proper understanding of merge conflict resolution.

GitHub Remote Repository
Add remote repository:
git remote add origin https://github.com/pranavmehta95/DevOps

Push project to GitHub:
git branch -M main
git push -u origin main
After pushing, all commits, branches, and files are visible on GitHub.



Key Concepts Learned
	•	Working directory, staging area, and repository
	•	Branch creation and management
	•	Merge operations
	•	Merge conflict resolution
	•	GitHub remote synchronization
	•	Writing structured documentation using Markdown


Challenges Faced
	•	Understanding merge conflicts initially
	•	Managing multiple branches correctly
	•	Ensuring clean and meaningful commit history

These challenges helped strengthen practical Git skills.


Conclusion

This project successfully demonstrates hands-on mastery of Git and GitHub.
By implementing proper branching strategies, resolving merge conflicts, and maintaining a clean commit history, this repository fulfills all the requirements of the Version Control Systems assignment.