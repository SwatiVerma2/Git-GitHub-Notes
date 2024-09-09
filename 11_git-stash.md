# Git Stash
The git stash command temporarily saves (or "stashes") the changes in your working directory without committing them, allowing you to switch branches or perform other tasks without losing your uncommitted work.

### How git stash works:
- If you have made changes to your files (both staged and unstaged) but you're not ready to commit them, git stash allows you to put these changes aside (stash them) and return to a clean working directory.
- Once you're ready, you can retrieve (or "apply") those stashed changes and continue working.
  
### Use Case:
You're working on a feature but need to switch to another branch to fix a bug or review a pull request. Instead of committing incomplete work, you can stash it to come back to later.

#### Basic Commands:

- `git stash` / `git stash -m "message"`: Stashes your changes (tracked files) and gives you a clean working directory.
  
   ![image](https://github.com/user-attachments/assets/8f32a2ad-e7c0-499e-8abf-d5f33a421fb5)

- `git stash list`: Lists all the stashes you have saved.

   ![image](https://github.com/user-attachments/assets/92cc3a24-d3e5-4aa7-8abb-0b93385ed0ac)

- `git stash pop`: Applies the most recent stash and removes it from the stash list.

   ![image](https://github.com/user-attachments/assets/897de2c9-a0bd-4f00-ab38-9a328a9ac0d3)

- `git stash apply` / `git stash apply stash@{1}`: Applies the most recent stash without removing it from the stash list.

   ![image](https://github.com/user-attachments/assets/afc2d2b8-b016-480b-a64a-3562baf693d1)

- `git stash drop`: Deletes the most recent stash.

   ![image](https://github.com/user-attachments/assets/77fd2600-953f-4f93-809d-af7bbb3a461f)

- `git stash clear`: To clear all stash
- `git stash branch "<branch-name>" "stash@{0}"` : The git stash branch <branch-name> <stash> command allows you to create a new branch from an existing stash and apply the stashed changes directly to that new branch. This is particularly useful when you realize that the work you stashed should actually be on a separate branch rather than on the branch you were initially working on.

  ![image](https://github.com/user-attachments/assets/1aa61818-9a35-45ac-8298-91bce4adac9a)



  
