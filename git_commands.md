# GIT SETUP
| Command                                            | Description             |
| -------------------------------------------------- | ----------------------- |
| git config --global user.name "Your Name"        | Set your name           |
| git config --global user.email "you@example.com" | Set your email          |
| git config --list                                | View current Git config |

# WORKING WITH REPOSITORIES
| Command                | Description                                    |
| ---------------------- | ---------------------------------------------- |
| git init             | Initialize a new Git repo in your local folder |
| git clone <repo-url> | Clone an existing GitHub repo to your system   |

# BASIC FILE OPERATIONS
| Command                   | Description                                  |
| ------------------------- | -------------------------------------------- |
| git status              | See current changes, tracked/untracked files |
| git add .               | Stage all changed files                      |
| git add <file>          | Stage a specific file                        |
| git commit -m "message" | Commit changes with a message                |
| git rm <file>           | Delete a file and stage the deletion         |

# BRANCHING AND MERGING
| Command                  | Description                         |
| ------------------------ | ----------------------------------- |
| git branch              | List all branches                   |
| git branch <name>       | Create a new branch                 |
| git checkout <name>     | Switch to a branch                  |
| git checkout -b <name> | Create and switch to a new branch   |
| git merge <branch>     | Merge a branch into the current one |

# REMOTE REPOSITORIES
| Command                       | Description                       |
| ----------------------------- | --------------------------------- |
| git remote -v               | View connected remote URLs        |
| git remote add origin <url> | Connect to a remote repo          |
| git push -u origin main     | Push to GitHub and set upstream   |
| git push                    | Push commits to the remote branch |
| git pull                    | Pull latest changes from remote   |

# VIEWING HISTORY
| Command             | Description                   |
| ------------------- | ----------------------------- |
| git log           | Show full commit history      |
| git log --oneline | Show short commit history     |
| git diff          | See changes not yet staged    |
| git diff --staged | See changes staged for commit |

# UNDOING MISTAKES
| Command                        | Description                             |
| ------------------------------ | --------------------------------------- |
| git restore <file>           | Undo changes in working directory       |
| git reset <file>             | Unstage a file                          |
| git reset --hard             | Discard all local changes (be careful!) |
| git checkout <commit> <file> | Revert file to a previous version       |

# GIT IGNORE
| File         | Description                                                              
| ------------ | ---------------------------------------------------------------------|
| .gitignore   | List of files/folders Git should ignore (e.g., node_modules/, *.log) |



