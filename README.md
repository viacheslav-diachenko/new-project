# new-project

# New-Project Setup Instructions

## Cloning the Repository


1. Open your terminal or Git Bash.
2. Clone the repository using the command:

   *git clone https://github.com/viacheslav-diachenko/new-project*

3. Navigate into the cloned repository directory using 'cd new-project'

## Working with Branches

### Creating a Development Branch

1. To create a new branch named 'development', use:

   *git branch development*

2. Switch to the 'development' branch:
   
   *git checkout development*

### Committing Changes

1. Add your changes to the staging area:

   *git add <file-name>*

2. Commit your changes with a descriptive message:

   *git commit -m "Your commit message"*

### Pushing Changes to GitHub

1. Push your changes to the 'development' branch:

   *git push origin development*

### Merging Development into Main

1. Switch to the 'main' branch:

   *git checkout main*

2. Merge changes from 'development':

   *git merge development*

3. Push the merged changes to GitHub:

   *git push origin main*





