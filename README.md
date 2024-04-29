# Git Assignment - <jinjiaacademy>


a. What is an issue?

An issue on GitHub is a way to track enhancements, tasks, or bugs for work on GitHub. It acts as a platform for discussion and planning related to specific tasks or problems associated with a project. Issues can be labeled, commented on, and assigned to users working on the project, providing a collaborative environment for managing project tasks.

b. What is a pull request?

A pull request is a method used in GitHub for requesting changes to be merged into a repository. It allows developers to tell others about changes they have pushed to a branch in a repository on GitHub. Once a pull request is opened, team members can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

c. How do I open up a pull request?

To open a pull request, follow these steps:
1. Push your changes to a branch in your repository on GitHub.
2. Navigate to the repository page on GitHub.
3. Click on the "Pull requests" tab.
4. Click the "New pull request" button.
5. Choose the branch that has your changes and the branch into which you want to merge the changes.
6. Click "Create pull request."
7. Add a title and description for your pull request.
8. Click "Create pull request" again to submit the pull request.

d. Step by step guide on how to add someone to your repository:

1. Go to your repository on GitHub.
2. Click on "Settings" and navigate to the "Collaborators & teams" tab.
3. Click on “Manage access,” then click on "Invite a collaborator."
4. Enter the GitHub username of the person you want to add and select them.
5. Click "Add collaborator" to send an invitation.
6. The invited person will receive an email with a link to accept the invitation.

e. What is the difference between git and GitHub?

Git is a version control system that lets you manage and keep track of your source code history. GitHub is a cloud-based hosting service that lets you manage Git repositories. While Git is a command-line tool, GitHub provides a web-based graphical interface. It also provides access control and several collaboration features, such as a basic task management tools for every project.

f. What does git diff do?

The `git diff` command is used to show the differences between two sources in a Git repository. It can show the changes between two commits, the changes between the staging area and the last commit, or the changes in the working directory that have not yet been staged.

g. What is the main branch?

The main branch (commonly referred to as "master" in older repositories) is the default development branch. When a repository is created, it automatically has a main branch. It is considered the authoritative branch where the stable codebase is maintained and is used for all development and production deployment processes.

h. Should we directly push our changes into the main branch?

It is generally recommended not to push changes directly to the main branch, especially in collaborative environments. Instead, changes should be made in separate branches and merged via pull requests after review. This practice ensures that the main branch remains stable and reduces the risk of introducing errors.