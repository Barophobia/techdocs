+++
title = "Git"
weight = 5
chapter = true
pre = "<b> - </b>"
+++

## Git 

### What is Git?

Git is a version management tool used to make collaborative efforts a lot easier.

### Creating a new repository:

To create a new repository using git you should cd to the folder you want to be a repository and type into your terminal:

```
git init
```

This will create a .git directory known as the working tree. 

### Checking the status of your repository

Using the 'git status' command will show you what branch you are using, changed files not staged for commit and files that are not currently tracked by git.

```
git status
```

### Adding files to your repository to be tracked
To add files to be tracked you will need to use 'git add' an example of this would be:

```
git add .
```

Using the command above will add all files inside the folder to be tracked. 