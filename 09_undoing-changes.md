# Undoing Changes

## Case 1 : Undo staged changes

1. Unstage a Specific File: 
      -  To unstage a specific file, keeping your changes in the working directory 
      - `git reset <file-name>`
    
2. Unstage All Files: To unstage all files, keeping changes in the working directory
      - This will remove all files from the staging area, but keep your changes in the working directory.
      - `git reset`

## Case 2 : Undo commited changes (for one commit)

1. Reset to the Previous Commit:
    - To undo the last commit while keeping changes in the working directory (useful if you want to edit or re-commit)
    - This command moves the current branch pointer back by one commit.
    - The changes from the undone commit will be left in your working directory and staging area.
    - `git reset HEAD~1`

## Case 3 : Undo Committed Changes (for many commits)

1. Reset to a Specific Commit:
    -  To undo commits up to a specific commit, keeping changes in the working directory and staging area
    -  This command will move the branch pointer to the specified commit and keep your changes.
    - `git reset <commit-hash>`

2. Reset to a Specific Commit and Discard Changes:
    - To reset to a specific commit and discard all changes (both staged and working directory)
    - This command will remove all changes after the specified commit, including those in the working directory.
    - `git reset -- hard <commit-hash>`
