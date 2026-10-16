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
<!-- Add instructions for cloning and setting up the repository -->

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
