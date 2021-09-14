# Git Basics



## Git Repository



### Getting a Git Repository

#### Initializing a Repository in an Existing Directory

- `git init`: start to track an existing project in Git
  - creates `.git` subdirectory that **contains a Git repository skeleton** which is all your necessary repository files
- `git add`: staging to start version-controlling existing files
- `git commit`: records the snapshot set up in staging area

#### Cloning an Existing Repository

- `git clone`:  get a copy of an existing Git repository
  - every version of every file for the history of the project is pulled down by default 
  - different **transfer protocol** options owner can set up to access Git repository and pros/cons of each (Ch4)



### Recording Changes to the Repository

- need to make some changes and commit snapshots of those changes into your repository each time the project reaches a state you want to record
- each file in the working directory can be in one of two states:
  - tracked: files that were in the last snapshot. They can be unmodified, modified, or staged.
  - untracked: files that were not in the last snapshot, nor in staging area



### Viewing the Commit History



### Undoing Things



