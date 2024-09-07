# GitHub

- GitHub is a web-based platform built on top of Git, a version control system, that allows developers to store, manage, and collaborate on code. 
- It provides a centralized space where developers can host repositories, track changes, and collaborate with others through features like pull requests, issues, and project boards.

Create an account on github > create a new repository(repo) > add a readme file > commit changes

# Git

- Git is a distributed version control system used to track changes in files and coordinate work on those files among multiple people. 
- It was created by Linus Torvalds in 2005 for the development of the Linux kernel and has since become the most widely used version control system in software development.

### Key reasons for Git's popularity:

1. **Version Control**: Git is primarily used for version control, allowing developers to track changes to their codebase over time. This enables them to revert to previous versions, compare changes, and maintain a history of all modifications.

2. **Collaboration**: Git facilitates collaboration among developers working on the same project. Multiple developers can work on different parts of the code simultaneously, and Git helps merge their changes seamlessly.

3. **Branching and Merging**: Git's branching and merging capabilities enable developers to work on new features or bug fixes in isolation (on separate branches) and later merge them back into the main codebase when ready.

4. **Code Reviews**: Git-based platforms like GitHub and GitLab support code review workflows, allowing developers to propose changes (via pull requests) and have them reviewed by peers before merging into the main branch.

5. **Backup and Recovery**: Git provides a robust backup mechanism, ensuring that the entire history of a project is preserved. In case of data loss or accidental changes, developers can recover previous versions of files easily.

6. **Continuous Integration and Deployment (CI/CD)**: Git integrates with CI/CD pipelines, enabling automated testing, building, and deployment of code changes. This helps in maintaining a consistent and reliable development workflow.

7. **Open Source Contribution**: Many open-source projects use Git for managing their source code repositories. Contributors can fork the project, make changes, and submit pull requests to contribute to the project.

8. **Tracking Changes in Documents**: Although Git is primarily used for code, it can also be used to track changes in other types of documents (e.g., documentation, configuration files) that benefit from version control.


## Installation for windows users

1. Download git bash - [Click to download Git](https://git-scm.com/download/win)
2. VS Code - [Click to download Git](https://code.visualstudio.com/download) 
3. To verify : `git --version`
   
## Configuring Git

`git config -- global user.name "your-name"`

`git config -- global user.email "your-mail-id"`

`git config -- list`
~ → root directory

![image](https://github.com/user-attachments/assets/6a483cdb-6697-416b-897f-542addd77a1e)

- Global: Global configuration settings are applied to all repositories on your system 
- Local: Local configuration settings are specific to a particular Git repository. Settings in the local configuration override settings in the global configuration for that specific repository.

   `code . ` on terminal will open VS Code
  
## Cloning a repo

1. To clone a repository on our local machine
  
  `git clone <- some link ->`

  Go to repo < code < https < copy the link

  ![image](https://github.com/user-attachments/assets/bacdfc85-67b9-4091-9a28-8344a74be172)

  ![image](https://github.com/user-attachments/assets/cec43cdd-4a59-4b78-8cc3-0f1d67e00ea0)

-   The local repository is the version of the Git repository that exists on your own computer.
-   The remote repository is a version of the repository hosted on a server, such as GitHub, GitLab, or Bitbucket.
  
2. To show the current state of the working directory and the staging area.
   
   `git status`
   
   ### Staging area
   
   - It is also known as the index, is an intermediate space where changes are gathered before they are committed to the repository. 
   - It allows developers to review and organize their changes before making a commit.
   
   ### When you run git status, it typically shows:
   
   - Changes not staged for commit / Modified : Files that have been modified but not yet added to the staging area (using git add).
   - Changes to be committed / Staged : Files that have been staged and are ready to be committed.
   - Untracked files: Files that are new and haven't been added to version control yet.
   - No changes / Unmodified: If everything is up to date and there are no modifications, it will show a message that the working tree is clean.

   Ex. Make few changes in the file in vs code then save it. It will show the files with yellow ‘M’ symbol which means modified.
   
   ![image](https://github.com/user-attachments/assets/30ab54a0-78b8-4573-b9ba-2e9720ceb992)

   Modified:
   
   ![image](https://github.com/user-attachments/assets/23670fb0-5969-45dd-a5d3-0016da720015)
   
   If we add a new file → untracked:

   ![image](https://github.com/user-attachments/assets/ddd2e2f2-fd5a-4801-a7a8-6a8f802dcd76)

   - If you have modified the file in your local system then we need to add and commit.
   - When files are added, the status is changed to staged
   - Commit : status  -> unchanged


