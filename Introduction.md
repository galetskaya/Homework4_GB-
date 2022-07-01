
# INTRODUCTION

This folder will contain the explanation of the usage of some GIT commands.

***The goals of this presentation are:***

* to reapeat the lecture material
* to have a practice with GIT and its commands
* to have some practice with MarkDown
* to keep Timur busy 
* something else probably, but nothing pops up in my head yet

<font size="1"> Remark: this project was written in english not because I am showing off, but because my macbook has danish keyboard and it is a little bit of suffering to use it in russian.</font>

# GIT INIT

The **_git init_** command is the first command that you will run on Git. The git init command is used to create a new blank repository. It is used to make an existing project as a Git project. Several Git commands run inside the repository, but init command can be run outside of the repository.

![Letsgo](start.jpg)

# GIT STATUS

The **_git status_** command is used to display the state of the repository and staging area. It allows us to see the tracked, untracked files and changes. This command will not show any commit records or information. Mostly, it is used to display the state between Git Add and Git commit command.

![200.gif](200.gif)

# GIT DIFF

The **_git diff_** command shows the differences between the files in two commits or between your current repository and a previous commit. This command displays changes denotes by headers and metadata for the files that have changed.

![leviOsa](hermiona.webp)

# GIT LOG

**_Git log_** is a utility tool to review and read a history of everything that happens to a repository. Multiple options can be used with a git log to make history more specific. Generally, the git log is a record of commits.


# GIT ADD

The **_git add_** command adds new or changed files in your working directory to the Git staging area. git add is an important command - without it, no git commit would ever do anything. Sometimes, git add can have a reputation for being an unnecessary step in development.

# GIT COMMIT

The **_commit_** command is used to save your changes to the local repository. Note that you have to explicitly tell Git which changes you want to include in a commit before running the "git commit" command. This means that a file won't be automatically included in the next commit just because it was changed.

<font size ="1">


The command should be used as git commit -m "comment"</font>



![DoIt](office.webp)

# GIT CHECKOUT

In Git, the term checkout is used for **the act of switching between different versions of a target entity**. The git checkout command is used to switch between branches in a repository. Be careful with your staged files and commits when switching between branches.