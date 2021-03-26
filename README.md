##                             GIT NOTES
* GIT is a "Distrubuted version contril system". Git is like dropbox for code


Two ways to work with git:
1. We'll make repos on GitHub and clone them to our laptop  (this a remote way)
2. We'll make repos on our laptop then add github as a remote and push to github. (this a local way) the steps are here : https://ds.codeup.com/fundamentals/git/

** the option 1 is the easiest way.**

Setup a Repo (one time setup) REMOTE

1. CREATE a new repository (name your respository and give it a description)
    Go to https://github.com/new   (name your respository and give it a description)
    Skip all the boxes and click the green "create repo" button
    Copy the SSH address of our new empty repo.
           my-data-science-notes.git
2. In your terminal, LOCATE the folder where you want to clone your new repository.
    cd will help you to go to your folder. 
    cd Desktop (it will take you to to your Desktop folder if you are  Home)
*       cd codeup-data-science
3. CLONE. type git clone and then paste the git clone address after that in your terminal (this makes a copy of the repo locally)
*        git clone git@github.com:cindyvillanuevads/my-data-science-notes.git
4. LOCATE your my-data-science-notes folder.
*        cd my-data-science-notes
5. VS CODE. Use VS code to make a file. 
*        code README.md
        * this commad will open VS Code and you can start typing notes. when you finish save the file (command + S)now you can close VS Code.
6. ADD. Adding the file. It is like putting a letter in an envelope
*       git add README.md
7. COMMIT. It is like a fancy signed, sealed, wax stamped fancy envelope from some fancy desk.
    * A.this option will open your editor so you can type the commit message. type the message save and close it.
*         git commit
    * B. If your commit message is kinda short, you can do:
*        git commit -m "this is my commit"
8. PUSH. Uploads any commits you have to your remotes.
*       git push
9. CHECK GITHUB. check your new repository on GitHub
       



## USEFUL COMMANDS

* git status = to show which files changed
* git diff = to see what has changed in those files. Before any adding/commiting shows changes
* git remote -v = shows all of your remotes


#### REMEMBER #####
*   add   (everytime you  do work, add lines to files, make new files, edit files, delete, whatever)
*   commit (early, commit often. commits should be a complete thought or fix or feature)
*   push   (your commits at least once or twice a day)