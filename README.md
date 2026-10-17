# COMP3104_Group13_Assignment

## Group Members
- **Leader:** Beatriz Ferreira (101176410) - [Github] (https://github.com/becarolf)
- **Member 2:** Daniel Alvarez (101589165) - [Github] (https://github.com/Dann1706)
- **Member 3:** Jenifa Joseph (101571040) - [Github] (https://github.com/Jenifaj8)
- **Member 4:** Leticia Rodrigues (101559381) - [Github] (https://github.com/ltprodrigues)
- **Member 5:** Ricardo Lima (101590278) - [Github] (https://github.com/Ricrdolimma)

## Project Description
This repository contains the group assignment for COMP3104 - DevOps.

The purpose of this project is to apply DevOps concepts and practices, focusing on version control, collaboration, branching strategies, and Continuous Integration (CI).

Throughout this assignment, team members work on individual branches, make regular commits and collaborate using Git and GitHub. The Project also introduces GitHub Actions to automate workflows and demonstrate CI/CD principles.

## Setup Instructions

The COMP3104 Group 13 repository can be cloned and accessed locally using Git. The following setup process allows team members to access project files and stay synchronized with the latest updates.

### Prerequisites

Ensure the following tools are available before setting up the repository:

- **Git:** For cloning the repository and managing version control.
- **GitHub Account:** For accessing the repository and collaborating with team members.
- **Code Editor:** Visual Studio Code or any preferred text editor for viewing and editing project files.

### Cloning the Repository

1. Open Git Bash or a terminal.
2. Clone the repository from GitHub:

   ```bash
   git clone https://github.com/becarolf/COMP3104_Group13_Assignment.git
   ```

3. Navigate to the cloned project directory:

   ```bash
   cd COMP3104_Group13_Assignment
   ```

### Verifying the Local Setup

Confirm that the repository has been cloned successfully by running:

```bash
git status
```

This command displays the current branch and the status of the working directory. A successful setup should show the `master` branch with a clean working tree.

The repository includes the individual student assignment files, `README.md`, and the `.github/workflows/` directory containing the GitHub Actions configuration.

### Keeping the Repository Updated

To ensure the local repository reflects the latest changes merged by the team, run:

```bash
git switch master
git pull origin master
```

These commands switch to the shared `master` branch and retrieve the latest updates from GitHub.

## CI/CD Pipeline
This project uses GitHub Actions to implement Continuous Integration (CI) and automate workflow execution.

The workflow is configured in .github/workflows/ and uses an Ubuntu runner (ubuntu-latest) to execute automated steps.

CI/CD Configuration:

GitHub Actions runs the workflow when changes are pushed to the repository.

The workflow executes predefined steps to verify successful execution.

Automated checks help the team identify potential issues during development.

Checking Pipeline Status:

Open the GitHub repository.

Navigate to the Actions tab.

Select the latest workflow run.

Review the execution results and logs.

A green checkmark indicates a successful run, while a red X indicates a failed run.

## Branching Strategy
Each member works on a personal branch named `STUDENTID-Name`. Members commit their own changes locally and push them to their branch. Changes are proposed to `master` through pull requests, where they can be reviewed before merging. Members should regularly pull updates from `master` into their own branch to stay current and reduce merge conflicts.
