# Resolving Merge Conflicts

- A merge conflict occurs when Git is unable to automatically merge the changes from two branches due to overlapping changes in the same part of a file. 
- These conflicts need to be manually resolved before completing the merge.

### Example:
- Make some changes in your file and commit those changes. (main branch)
- Add some other changes in the same line on `feature1` branch.
- `git diff main`
  
  ![image](https://github.com/user-attachments/assets/561174a9-97b9-4f2f-9460-bfe024443a2c)
  
- Merge conflict occured
  
  ![image](https://github.com/user-attachments/assets/a36d15b3-fbf2-4643-aac1-d1a4bf89dba9)

- Resolving Merge Conflicts
  
  ![image](https://github.com/user-attachments/assets/87e5e5d7-11f2-4b04-a5a1-be42dca22144)

  ![image](https://github.com/user-attachments/assets/8a5fabf2-3806-42b4-a1f8-f3ea1ff3df6b)
  
- Here, the changes are from both branches.
  
  ![image](https://github.com/user-attachments/assets/a2091f72-1503-413d-a736-a71f7b4dce1f)

- Add & Commit the changes --> resolved
  
  ![image](https://github.com/user-attachments/assets/fbf69a0c-82f6-4386-9bcb-aa386134711c)

- `git diff main`
  
  ![image](https://github.com/user-attachments/assets/03e5052b-e4eb-4a1d-8bf7-ece5f3f0bd07)

- merging feature1 with main: `git merge feature1`

  ![image](https://github.com/user-attachments/assets/c61e6f48-e286-49bf-8e04-7a8c9081d978)

- Puhsing the changes to github: `git push origin main`

  ![image](https://github.com/user-attachments/assets/4bc63d9f-9fcd-4640-8529-964f959e3c03)
