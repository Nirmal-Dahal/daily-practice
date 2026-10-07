# for New Project
1. Git Initilization
    ```
    git init
    ```
2. Add Files and folder to gits for tracking
    ```
    git add .
    ```
    **`Note: . is for all files and folder, in place of . we can add files name.`**
3. After  completing: save  all codes as some version
    ```
    git commit -m "[Your_commit_message]"
    eg: gt=it commit -m "project initilized"
    ```
4. Optional step: changing main branch
    ```
    git branch -M "[Your_main_branch_name]"
    ```
     **`Note: Default branch is always "maseter"`**
5. Add remote repo link or repository url
    ```
    git remote add origin "[youe_repository_url]"
    ```
6. Push the recent commited code to remote
    For first time:
    ```
    git push -u origin "[your_current_branch_name]"
    ```
    Later (if one pushh is already done using -u: upstream)
    ```
    gitpush
    ```
7. To preview the current git status
    ```
    git status
    ```
8. To check the linked remote url
    ```
    git remte -v
    ```
9. 