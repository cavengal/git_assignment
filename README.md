# Git Assignment - cavengal

a. What is an issue?

<br>An "issue" is feature used for tracking tasks, enhancements, bugs, or any other type of item that needs attention within a software project.<br>
Github, since it's a web based platform for hosting Git repositories, provides an issue tracking system in which users can discuss problems, suggest new features, or ask questions related to a particular repository. They serve as a centralized hub for collaboration and communication within a project.<br>
Git, on the other hand, doesn't inherently have an issue tracking feature. Nevertheless an issue might be discussed in Git if managed through a centralized system like a project management tool or via the command line interface using certain conventions.<br><br>

b. What is a pull request?

<br>A pull request is a feature in version control systems like Git and platforms like GitHub, that allows developers to propose changes to a repository hosted on a platform like GitHub.<br>
They are a key step in collaborative software development cycle. Once changes are created for a new feature or bug fix, to cite a few, developers push their branch changes to the remote repository and once there, they create a pull request to review and discuss changes with the project collaborators and maintainers.<br> 
Pull requests are usually created in response to an issue, especially if the issue describes a bug that needs fixing or a feature that needs implementing.<br> <br>

c. How do I open up a pull request?

<br> On GitHub, once a pull request is created by switching to the branch containing your changes, and clicking on "Compare & pull request" button, filling in the details for your pull request and submitting the pull request, one can find the pull request under "Pull requests". There you can continue to the review and feedback process until maintainers approve changes to eventually merge the pull request to the main branch of the original repository <br><br>

d. Give me a step by step guide on how to add someone to your repository.

<br>1. Navigate to Your Repository: Go to the GitHub website and navigate to the repository to which you want to add a collaborator.<br>
2. Repository Settings: In the repository, click on the "Settings" tab located near the top-right corner of the page.<br>
3. Manage Access: In the Settings menu, find and click on the "Manage access" or "Collaborators" option. This will take you to the page where you can manage who has access to the repository.<br>
4. Invite Collaborator: In the Collaborators section, you'll see a field to invite collaborators. Enter the GitHub username, email address, or organization name of the person you want to add as a collaborator.<br>
5. Select Permissions: After entering the collaborator's information, you'll usually have the option to select their permissions level. GitHub offers several permission levels, including:<br>
Read: Allows the collaborator to view the repository and its contents.<br>
Write: In addition to read access, allows the collaborator to push commits to the repository.<br>
Admin: Full access to the repository, including the ability to manage collaborators, change repository settings, and delete the repository.<br>
6. Send Invitation: Once you've selected the appropriate permissions, click on the "Add [username]" or "Send invitation" button to send an invitation to the collaborator. <br>
7. Confirmation: The collaborator will receive an email notification informing them that they've been invited to collaborate on the repository. They'll need to accept the invitation to gain access.<br>
8. Accept Invitation: The invited collaborator should navigate to their GitHub account, go to the "Invitations" section of their profile, and accept the invitation to collaborate on the repository.<br>
9. Collaborating: Once the invitation is accepted, the collaborator will have the specified access permissions to the repository. They can then clone the repository, make changes, and push commits just like any other collaborator.<br><br>

e. What is the difference between git and GitHub?

<br>Git is a version control system (VCS) that helps developers manage and track changes to their codebase, while GitHub is a web-based platform built around Git that provides additional features for collaboration, project management, and community interaction. Git is the underlying technology, while GitHub is a service that leverages Git to offer a comprehensive solution for hosting and collaborating on software projects. <br><br>

f. What does git diff do?

<br>git diff is a Git command used to display the differences between changes in various parts of a Git repository. Some common uses depending on the arguments you add to the command:<br>
1. It shows differences between changes in the working directory and the last commit.<br>
2. It can display differences between changes in the staging area (index) and the last commit.<br>
3. You can specify particular files or directories to see differences.<br>
4. It compares changes between different commits, branches, or commits and branches.<br>
5. By default, it outputs differences in the unified diff format, showing added and removed lines.<br>

g. What is the main branch?

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
