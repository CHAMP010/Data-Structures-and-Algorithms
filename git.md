# Git and Github

1. Initialize a git repository.
   ```
   git init
   ```
2. Track changes.
   ```
   git status
   ```
3. Add all untracked items to staged area.
   ```
   git add .
   ```
4. Add only particular untracked item to staged area.
   ```
   git add file.ext
   ```
5. Commit staged changes.
   ```
   git commit -m "message"
   ```
6. Restore staged changes.
   ```
   git restore --staged file.ext
   ```
7. Get history of all commits.
   ```
   git log
   ```
8. Unstage all the staged changes above/after the provide commit hash.
   ```
   git reset commithash
   ```
9. Stash all the staged changed to last.
   ```
   git stash
   ```
10. Bring back all the stashed changes.
    ```
    git stash pop
    ```
11. Clear all the stashed changes.
    ```
    git stash clear
    ```
12. Link your folder with github repositories remotely.
    ```
    git remote add origin remote url
    ```
13. Push the changes to origin master branch.
    ```
    git push origin master
    ```
14. Get all the Links to remote github repo.
    ```
    git remote -v
    ```
15. Create branch and Commit changes on new branch.
    ```
    git branch branchname
    git checkout branchnames
    ```
16. Merge the branch into main.
    ```
    git merge branchname
    ```
17. Add the upstream url (url from where you forked a repo)
    ```
    git add upstream upstreamurl
    ```
