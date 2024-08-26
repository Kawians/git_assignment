# Git Assignment - <Kawians>

## a. What is an issue?
An issue on GitHub is a tool for tracking tasks, bugs, or requests related to a project. It allows users to report problems, suggest improvements, and discuss various aspects of the project. Issues help manage and prioritize work within a project.


## b. What is a pull request?
A pull request on GitHub is a way to propose changes to a codebase. It allows contributors to submit their code changes for review and discussion before merging them into the main project. It facilitates code review, collaboration, and ensures that changes are properly vetted before being integrated.


## c. Describe the steps to open a pull request?
Fork and Clone: If you're not a collaborator, fork the repository and clone it to your local machine.
Create a Branch: Make a new branch for your changes.
Make Changes: Edit the code and commit your changes to your branch.
Push Changes: Push the branch with your changes to your remote repository.
Open Pull Request: Go to the GitHub repository page, select the "Pull Requests" tab, and click "New Pull Request." Choose your branch and submit the pull request.



## d. Describe the steps to add a collaborator to a repository (share write permissions)
To add a collaborator to a GitHub repository with write permissions:

Go to Repository Settings: Navigate to the repository on GitHub and click on "Settings."
Select "Collaborators & teams": Click on the "Collaborators & teams" option in the sidebar.
Add Collaborator: In the "Collaborators" section, enter the GitHub username of the person you want to add and click "Add collaborator."
Set Permissions: Choose "Write" permissions to allow them to push changes and manage issues.


## e. What is the difference between git and GitHub?
Git is a version control system used to track changes in code and manage source code history. It operates locally on your computer.

GitHub is a web-based platform that hosts Git repositories online, allowing for collaboration, sharing, and remote management of code. It provides additional features like pull requests, issue tracking, and project management tools.


## f. What does git diff do?
The git diff command shows the differences between files or commits. It displays changes in code between the working directory and the index (staging area), between the index and the last commit, or between any two commits. This helps you review changes before committing or merging.


## g. What is the main branch?
The main branch (often named main or master) is the default branch in a Git repository where the stable and production-ready code is usually maintained. It serves as the central branch from which other branches are created and where changes are merged.


## h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it's generally better to create and work on separate branches for features or changes. Once changes are tested and reviewed, you can merge them into the main branch. This approach helps manage code more effectively and reduces the risk of introducing errors directly into the main branch.