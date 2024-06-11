**What is ‘Staging Area’ or ‘Index’ in GIT?**  
Before committing a file, it must be formatted and reviewed in an intermediate area known as the ‘Staging Area’ or ‘Indexing Area’.
```
git add <file_name>
```


**What is Git Stash?**  
Let's say you’ve been working on part of your project, things are in a messy state and you want to switch branches for some time to work on something else. The problem is, you don’t want to do a commit of your half-done work just so you can get back to this point later. The answer to this issue is Git stash. Git stashing takes your working directory, that is, your modified tracked files and staged changes, and saves it on a stack of unfinished changes that you can reapply at any time.

**What is Git stash drop?**  
The `git stash drop` command is used to remove the stashed item. It will remove the last added stash item by default, but it can also remove a specific item if you include it as an argument.

> For example, to remove a particular stash item from the list of stashed items:
```
git stash list
```

This will display the list of stashed items:
```
stash@{0}: WIP on master: 049d080 added the index file
stash@{1}: WIP on master: c265351 Revert “added files”
stash@{2}: WIP on master: 13d80a5 added number to log
```

**What is the function of ‘git config’?**  
Git uses our username to associate commits with an identity. The `git config` command can be used to change our Git configuration, including your username.

> For example, to add a username and email id to associate commits with an identity:

```
git config --global user.name "Your Name"
```

This command will add your username.
```
git config --global user.email "Your E-mail Address"
```


This command will add your email id.
