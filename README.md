# Git Control Guidelines for Interns

## Introduction
Welcome to the team! As an intern, you'll be contributing to our projects through Git version control. This document outlines the steps you should follow when pushing code to our repositories.

## Setting Up Your Environment
Before you start working with Git, ensure you have Git installed on your system. You can download and install Git from [git-scm.com](https://git-scm.com/). Additionally, make sure you have access to the project repository and necessary permissions for branching and pushing changes.

## Workflow Overview
Our Git workflow follows a branching model to manage changes efficiently. Here's an overview of the process:

- Create a new branch off the main branch for each feature or bug fix.
- Make changes to the code in your branch.
- Push your branch to the remote repository.
- Create a pull request (PR) to merge your changes into the main branch.
- Assign a reviewer to your PR.
- After approval, merge your branch into the main branch.

## Step-by-Step Guide
Follow these steps to push your code changes:

### Create a New Branch

```bash
git checkout main               # Switch to the main branch
git pull origin main            # Ensure your main branch is up to date
git checkout -b feature-branch  # Create a new branch for your feature or bug fix
```
### Make Changes

Make the necessary changes to the codebase within your feature branch. Ensure your changes are focused and well-tested.


### Push Your Branch

```bash
git push origin feature-branch  # Push your branch to the remote repository
```

### Create a Pull Request

Navigate to the repository on GitHub. Locate the option to create a pull request and select your feature branch as the source and the main branch as the target.

### Assign a Reviewer

Assign a team member to review your pull request. This person will provide feedback and approve the changes if they meet the project standards. This person must review and test your changes to ensure stability of the main branch.

### Merge Changes

After your PR has been approved and tested by at least one other person, merge your branch into the main branch using the merge button on the PR page.

## Best Practices

-   Write clear and descriptive commit messages.
-   Keep your branches and commits focused on specific tasks.
-   Regularly pull changes from the main branch to keep your feature branches up to date.
-   Communicate with your team members about your progress and any potential conflicts.

##  
If you have any questions or encounter issues, don't hesitate to reach out to your mentor or team lead for assistance. Happy coding!
