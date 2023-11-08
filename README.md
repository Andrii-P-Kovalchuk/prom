This is README file.

## Step-by-step instruction.
1. Create new directory "new-project":
 - ``mkdir new-project`` 
2. Change current directory to "new-project":
 - ``cd  new-project``
3. Initialize a new public Git repository inside the "new-project" directory:
 - ``git init``
4. Create a new branch called "development" and switch to it. 
 - ``git checkout -b  "development"``
5.  Commit changes to the "development" branch with a commit message.
 -  ``git add README.md``
 -  ``git commit -m "File README.md changed"``
6. Merge changes from the "development" branch into the "main" branch. Before merging change to branch "main".
 - ``git checkout main``
 -  ``git marge development``
