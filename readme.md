# Working Directory
- Where all our files, directories, and changes are living all the time

# Staging Area
- Files and directories that we explicitly add to the staging area (via git add)

# Repository
- Where all our snapshots are stored (via git commit)

# Adding multiple files of a certain type
- git add *.<file extension>

# Adding all files in the directory
- git add .
- git add -A

# Removing files
- git reset HEAD <file>

# Ignoring files
- create hidden .gitignore file
- insert name of files that git should ignore
- add and commit as per usual

# Git Branches
- Listing all branches
* git branch

- Adding a branch
* git checkout -b <name of feature branch>

- Changing branches
* git checkout <name of branch>

- Merging a branch
* git merge <name of feature branch to be merged>

- Removing a branch
* git branch -d <name of branch to be removed>

# Github
- add remote repository
* git remote add origin https://github.com/arwinzen/git_intro.git
* git remote -v
* git push -u origin master

      0-----0-----0-----0       (side branch)
      /
0-----0-----0-----0-----0       (master branch)
