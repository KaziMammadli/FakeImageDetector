Using GitHub: Repositories, Pull Requests, and Issues
1. Repositories
A repository (repo) is where all your project files and version history are stored on GitHub.

Creating a Repository
Go to GitHub and log in.
Click on the + (New Repository) button.
Choose a repository name and set it as public or private.
Check "Initialize this repository with a README" (optional).
Click "Create repository".
Uploading Files to a Repository
Open the repository on GitHub.
Click "Add file" > "Upload files".
Drag and drop files or click "Choose your files".
Add a commit message (e.g., "Initial upload").
Click "Commit changes".
2. Branches and Pull Requests (PRs)
What is a Branch?
A branch is a copy of the main code where you can make changes without affecting the main branch. Once changes are tested, they can be merged into the main branch.

Creating a Branch on GitHub
Open your repository.
Click on the "main" branch dropdown (top left).
Type a new branch name (e.g., feature-login).
Click "Create branch".
Making Changes in a Branch
Switch to your branch from the branch dropdown.
Edit or upload files.
Click "Commit changes" after making edits.
Creating a Pull Request (PR)
A Pull Request (PR) is used to propose changes from one branch to another (e.g., from feature-login to main).

Open the repository.
Click "Pull requests" > "New pull request".
Choose the base branch (main) and the compare branch (your branch).
Review changes and add a description.
Click "Create pull request".
Team members can review and comment before merging.
Merging a Pull Request
Go to the Pull Requests tab.
Open the PR.
Click "Merge pull request" > "Confirm merge".
After merging, you can delete the branch.
3. Issues
Issues are used for reporting bugs, requesting features, or discussing tasks in a project.

Creating an Issue
Open the repository.
Click "Issues" > "New Issue".
Add a title and description of the issue.
Assign it to a team member (optional).
Click "Submit new issue".
Closing an Issue
Open the issue.
Click "Close issue" (if it's resolved).
If it’s fixed in a pull request, link the issue in the PR by writing:
nginx
Copy
Edit
Fixes #issue-number
Once the PR is merged, the issue will close automatically.
Summary
🔹 Repositories: Store your project files.
🔹 Branches: Work on different features separately.
🔹 Pull Requests: Propose changes and merge branches.
🔹 Issues: Track bugs and feature requests.

This way, you can manage your project entirely from GitHub without using Git Bash! 
