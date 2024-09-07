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
