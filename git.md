# Git321



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



### Tagging

Git tags specific points in history as being important. Use this functionality to mark release points(v1.0 and so on).

#### Tag Types

- lightweight: a pointer to a specific commit
- annotated: stored as full objects in the Git database with additional information like tagging message.



## Branch Management

- `git branch`: list all the local branches

- `git branch  -v`: list all the local branches together with the latest commit
- `git branch --merged`: list all branches that are already merged into the branch you're on 
- `git branch --no-merged`: list all branches that are not merged in yet
  - listed branches cannot be deleted with `-d`, has to be done with `-D`



### Branching Workflows

- Long-Running Branches
  - the stable branches are farther down the line in your commit history, and the bleeding-edge branches are farther up the history
- Topic Branches



