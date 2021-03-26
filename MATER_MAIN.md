## HOW TO CHANGE BRANCH MASTER TO MAIN 
1. Locate your repository (my-data-science-notes)
*       $cd Desktop/codeup-data-science/my-data-science-notes/
2. Check status
*       $git status
    On branch master
    Your branch is up to date with ‘master’.
3. Go to GITHUB and locate you repository.
4. Go to settings > Branches and change the default branch to main
5. It is going to give you the following commands. 

*       git branch -m main
*       git fetch origin
*       git branch -u origin/main main
*       git remote set-head origin -a
6. Copy the commands and paste in your terminal.
7. Check toy git status
*       git status
    you will see:
*   On branch main
*   Your branch is up to date with 'origin/main'.

*   nothing to commit, working tree clean