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
17. Add the upstream url (url from where you forked a repo).
    ```
    git add upstream upstreamurl
    ```
18. Force push (when repo has more thing than your git folder).
    ```
    git push origin master -f
    ```
19. Fetch all changes from upstream.
    ```
    git fetch --all --prune
    git reset --hard upstream/main
    ```
20. Get or Pull the changes from upstream.
    ```
    git pull upstream main
    ```
21. Merge multiple commits usign rebase.
    ```
    git rebase -i commithash
    ```
    All the commit above commithash will go to rebase. Use Pick (p) and Squash (s) to merge commits. all the squash commit will be merged to first Pick commit above them.
22. Hard reset to remove commit.
    ```
    git reset --hard commithash
    ```
23. When multiple commits are made from different branches or by user to a common line or code creates conflict which can be resolved using github desktop.
