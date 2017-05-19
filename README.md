# Working Directory
- Area where all of our files and directories and changes are living all the time
mkdir <name>

git init

git status

# Staging Area
- Files and directories that we explcitly addd to the staging area

# Git Repository
- Where all our snapshots are stored

# Adding multiple files of a certain type
git add <filename>
git add *.html

# Adding all files in directory (including hidden)
git add -A

# Removing files
git reset HEAD <filename>
git rm --cached <filename>

# Ignoring files
touch .gitignore
echo <filename> >> .gitignore 

# Git Branches
- Listing all branches
git branch
- Adding a branch
git branch -b <name>

        /-------0-------0-------0
       /                       /
0------0-----0-----0-----0-----0

- Changing branches
git checkout <name>

- Merging a branch
- git merge <name>
        /-------0-------0----\
       /                      \
0------0-----0-----0-----0-----0

- Removing a branch
git branch -d <name>

# create GitHub Repo
- git remote add origin https://github.com/leonschulman1982/intro-to-git.git
- git remote -v
- git push -u origin master