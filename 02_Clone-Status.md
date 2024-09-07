## Cloning a repo

To clone a repository on our local machine : `git clone <- some link ->`

 Go to repo < code < https < copy the link

  ![image](https://github.com/user-attachments/assets/bacdfc85-67b9-4091-9a28-8344a74be172)

  ![image](https://github.com/user-attachments/assets/cec43cdd-4a59-4b78-8cc3-0f1d67e00ea0)

-   The local repository is the version of the Git repository that exists on your own computer.
-   The remote repository is a version of the repository hosted on a server, such as GitHub, GitLab, or Bitbucket.

## Checking urrent status
To show the current state of the working directory and the staging area. : `git status`

### Staging area
   
- It is also known as the index, is an intermediate space where changes are gathered before they are committed to the repository. 
- It allows developers to review and organize their changes before making a commit.
   
### When you run git status, it typically shows:
   
- Changes not staged for commit / Modified : Files that have been modified but not yet added to the staging area (using git add).
- Changes to be committed / Staged : Files that have been staged and are ready to be committed.
- Untracked files: Files that are new and haven't been added to version control yet.
- No changes / Unmodified: If everything is up to date and there are no modifications, it will show a message that the working tree is clean.

Example:  Make few changes in the file in vs code then save it. It will show the files with yellow ‘M’ symbol which means modified.
   
![image](https://github.com/user-attachments/assets/30ab54a0-78b8-4573-b9ba-2e9720ceb992)

Modified:
   
![image](https://github.com/user-attachments/assets/23670fb0-5969-45dd-a5d3-0016da720015)
   
If we add a new file → untracked:

![image](https://github.com/user-attachments/assets/ddd2e2f2-fd5a-4801-a7a8-6a8f802dcd76)

- If you have modified the file in your local system then we need to add and commit.
- When files are added, the status is changed to staged
- Commit : status  -> unchanged
