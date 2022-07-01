# Linea de Comandos TERMINAL con GitBash:

![image-20220503-062950](https://user-images.githubusercontent.com/91127281/176974226-25024a4b-a1be-48b2-99c0-1e1fd4f8b61a.png)


# Linea de Comandos GIT con GitBash:

![image-20220617-193235](https://user-images.githubusercontent.com/91127281/176974243-7e39da3f-6619-45dd-b3b6-4f796f59267c.png)


# Git — Most frequently used commands

Git: Version control system to track changes in your projects.
It is also used to push and pull changes from remote repositories like GitHub, GitLab, BitBucket, etc.GitLab, GitHub, BitBucket: Services that allow to host your project as a remote repository and serve as repository managers that also have additional features to help SDLC(Software Development Life Cycle) and CI(Continuous Integration), CD(Continuous Deployment).

# Workflow:

![1_ZG8OzO2oTPi6cwm_e1h7rw](https://user-images.githubusercontent.com/91127281/176974251-642714ec-66d2-4f98-b3b9-35ce0d5d0e0b.png)


**Workspace ↔ Staging ↔ Local Repository ↔ Remote Repository**

# 1\. git — version

Display version of git. Also used to check whether git is installed or not.

# 2\. git config

```
## Set
git config --global user.name "Harsh Singhal"
git config --global user.email "harshsinghal726@gmail.com"## Check
git config --global user.name
git config --global user.email
```

# 3\. git init

Convert an existing unversioned project(workspace) to git repository or to create a new empty git repository.

Executing this command creates a `.git` subdirectory, which contains all the metadata for the new repository. This metadata includes subdirectories for objects, refs, and template files. A `HEAD` file is also created which points to the currently checked out commit.

# 4\. git clone

Download an existing git repository to your local computer.

`git clone -b branch_name <git url>:` The `-b` argument lets you specify a specific branch to clone instead of the branch the remote `HEAD` is pointing to, usually the master branch.

**git init vs git clone:** At a high level, they can both be used to _initialize a new git repository_. However, `git clone` is dependent on `git init`. Internally, `git clone` first calls `git init` to create a new repository. It then copies the data from the existing repository.

# 5\. git status

Display:

*   Current branch
    
*   Files that have differences between _Workspace ↔ Staging area_ (Untracked(new) files and Unstaged changes)
    
*   Files that have differences between _Staging ↔ Local Git Repository_ (Uncommitted changes)
    

# 6\. git add

Add changes in the workspace to the staging area.

_Workspace → Staging area_

# 7\. git commit

Add changes in the staging area to the local Git repository

`git commit`: _Staging area → Local git repository_

`git commit -a`: _Workspace → Local git repository_ (Untracked files are not included, only those that have been added with `git add` at some point)

`git commit -m ‘commit message’`

# 8\. git push & git pull

**Push:** Add changes in the local git repository to the remote repository

`git push <remote> <local>`: Local git repository _→ Remote git repository_

**Pull:** Update local git repository from the corresponding remote git repository

`git pull <remote> <local>`:Local git repository ← Remote git repository

# 9\. git branch

List all local branches.

`git branch -a`: List all remote branches as well

`git branch -d <branch>`: Delete the specified branch

`git branch <new branch>`: Create a new branch

# 10\. git checkout

Navigate between different branches.

`git checkout <branch>`

`git checkout -b <new branch>`: Create a new branch from your current branch and switch to it.

# 11\. git merge

Integrate changes from multiple branches into one.

`git merge <branch>`

# 12\. git remote

Manage connections to remote repositories.

It allows you to show which remotes are currently connected, but also to add new connections or remove existing ones.

`git remote -v`: List all remote connections

`git remote add <name> <url>`: Create a new remote connection

`git remote rm <name>`: Delete a connection to a remote repository

`git remote rename <old name> <new name>`: Rename a remote connection

# 13\. git fetch

Update local git repository from the corresponding remote git repository. Git fetch does not change your workspace, it keeps the fetched content separate until it is merged.

`git fetch <remote> <local>`

`git checkout <remote>/<local>`: To view the change

**git fetch vs git pull:** _git pull = git fetch + git merge_

# 14\. git log

Display committed snapshots.

# gitignore:

A text file which tells which files and folders to ignore in a project.

[https://www.genbeta.com/desarrollo/aprende-a-programar-colaborativamente-git-jugando-a-oh-my-git-videojuego-libre-al-que-tu-puedes-contribuir](https://www.genbeta.com/desarrollo/aprende-a-programar-colaborativamente-git-jugando-a-oh-my-git-videojuego-libre-al-que-tu-puedes-contribuir)
