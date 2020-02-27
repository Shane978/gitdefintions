# terminal definitions
- pwd: print working derictory
- ls: list all of files and directories inside of current
- cd [new directory to new directory]: Changge current working directory to new.
- mkdir: [NaomeofDirectory] make new directory
- touch [filename]: makes a new file
- nano [filename]: opwens new directory

# Git Hub notes
- Version Control - a system that records changes to a file over time so that you can recall specific versions later.
- VCS - Version Control System that allows you to revert sselected file or an entire project back to a previous state, 
- distributed VCS - instead of chedking out a snapshot a developer clones the entire project with all of its hisory to a local client.
- Working Directory - A single snapshot of the current project.
- Staging Area - Is a single file in the >Git directory that stores information about what will go in the next commit.
- Git Directory - the meta data and object database for your project.
- Unmodified - means the file is..uh...unchanged.
- Modified - means you have changed a file but have not commitied tkhose changes.
- Staged - means you have marked a changed file to go into the next commit (snapeshot).
- Committed - means the data in stored in the local database.

- git - <branchname> - create a new branch with the given name.
- git checkout <branchname> - switch to new branch.
- git checkout < branchname> _ create new branch and switch to it.
- gitbranch <branchname> - delete existing branch with given name.


# Git Definitions 
- git merge (BranchNameToMerge): merges the branch named into the current branch you are working on.

# GitFlow
- Master branch - only stable tested code.
- Develop branch - intergration branch for new features if it is going to brek, we want it to break on develop.
- Topic branches - branch from develop for feature development or bug fixes. Topic branchs are merged back into develop and never interact with the master branch.

