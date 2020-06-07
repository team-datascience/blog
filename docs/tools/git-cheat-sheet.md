---
id: git
title: git commands && cheat sheet
sidebar_label: Git
---
**# git && commands**

# **git**

Git is a distributed version control system (DVCS). "Distributed" means that all developers within a team have a complete version of the project. A version control system is simply software that lets you effectively manage application versions.
 you'll be able to do the following:

 *  Keep track of all files in a project
 *  Record any changes to project files
 *  Restore previous versions of files
 *  Compare and analyze code
 *  Merge code from_ different computers and different      team members.

# Git Commands

## Configuring Git

**git config**

``` Usage: git config –global user.name “[name]”
    Usage: git config –global user.email “[email address]” 
    Usage: git config --global color.ui true
    Usage: git config --list
```
![iloveA-i](assets/image.png)

The git config command is a convenience function that is used to set Git configuration values on a global or local project level. These configuration levels correspond to . gitconfig text files. Executing git config will modify a configuration text file.


![iloveA-i](assets/list.png)

## Starting a New Local Repository with Git

**git init**
```
Usage: git init [repository name]
```


The "init" command stands for initialize. Once you run "git init", Git will initialize a hidden directory called ".git" in the project's root directory. And you'll get a confirmation that your deposit box is ready! What's next? You might want to know the status of your box: does it store anything yet? To know the Git status, you'll need to run:

![iloveA-i](assets/init.png)


 **git status**

```
  Usage: git status
```

 The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. 


![iloveA-i](assets/status.png)

**git branch**
```
 Usage: git branch
```
The "branch" command helps you create and list branches. It's the go-to command when it comes to managing any aspect of your branches. No matter if in your local repository or on your remotes.

![iloveA-i](assets/branch.png)

**git add**

```
Usage: git add *
```

 which adds changes in the working directory to the staging area. With the help of this command, you tell Git that you want to add updates to a certain file in the next commit.

![iloveA-i](assets/add.png)

**Git Commits**

```
Usage: git commit -m "message"
```
The "commit" command is used to save your changes to the local repository.Using the "git commit" command only saves a new commit object in the local Git repository.

![iloveA-i](assets/commit.png)

## Push and Pull To and From a Remote Repository

**git clone**

```
Usage:git clone -b 'branch_name' <git_url>
                or
Usage:git clone <git_url>
```

git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.


![iloveA-i](assets/clone.png)

**git push**

```
Usage:git push
```

The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.


![iloveA-i](assets/clone.png)

**git pull**

```
Usage:git pull
```
git clone means you are making a copy of the repository in your system. git fork means you are copying the repository to your Github account. git pull means you are fetching the last modified repository. Clone is generally used to get remote repo copy


![iloveA-i](assets/pull.png)


# Basic Snapshotting
Command  | Description
------- | -------
 git status | Check status 
 git add [file-name.txt] | Add a file to the staging area
 git add -a | Add all new and changed files to the staging area
 git commit -m "[commit message]" |Commit changes
 git rm -r [file-name.txt] |git rm -r [file-name.txt] | 

# Branching & Merging


Command | Description
------- | ---------
git branch| List branches (the asterisk denotes the current branch)
git branch -a | List all branches (local and remote)
git branch [branch name]|  Create a new branch
git branch -d [branch name]| Delete a branch
git push origin --delete [branch name]| Delete a remote branch
git checkout -b [branch name] | Create a new branch and switch to it
git checkout -b [branch name] origin/[branch name] | Clone a remote branch and switch to it
git branch -m [old branch name] [new branch name] | Rename a local branch
git checkout [branch name] | Switch to a branch
git checkout | Switch to the branch last checked out
git checkout -- [file-name.txt] | Discard changes to a file
git merge [branch name] | Merge a branch into the active branch
git merge [source branch] [target branch] |Merge a branch into a target branch
git stash |Stash changes in a dirty working directory
git stash clear  |Remove all stashed entries 



# Sharing & Updating Projects

Command |Description
------- | -------
git push origin [branch name] | Push a branch to your remote repository
git push -u origin [branch name] | Push changes to remote repository (and remember the branch)
git push | Push changes to remote repository (remembered branch)
git push origin --delete [branch name] | Delete a remote branch
git pull | Update local repository to the newest commit
git pull origin [branch name] | Pull changes from remote repository
git remote add origin ssh://git@github.com/[username]/[repository-name].git | Add a remote repository
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git | Set a repository's origin branch to SSH


# Inspection & Comparison

Command | Description
------- | -------
 git log | View changes
git log --summary | View changes (detailed)
git log --oneline | View changes (briefly)
git diff [source branch] [target branch] | Preview changes before merging
