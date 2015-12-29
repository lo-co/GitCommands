# Git Commands

This is just a repository of some ``git`` commands that I have found that I use on a regular basis.

## Cloning a repository

To clone a directory:

``git clone https://github.com/user-name/repo``

Cloning a repository with __submodules__:

``git clone --recursive https://github.com/user-name/repo``

## Working with submodules

A good resource for submodules can be found [here](https://git-scm.com/book/en/v2/Git-Tools-Submodules).  To add a submodule:

``git submodule add https://github.com/user-name/repo``

This adds the submodule to the top-level directory.  To add the module to a different directory, you can append the path as follows:

``git submodule add https://github.com/user-name/repo [path]``

## Resetting to another version

```
git add --all
git commit -m "Message for commit"
git reset --hard origin/master
```

# SSH 

To SSH from the terminal use the following command:

```
ssh user@address
```

where ``user`` is the user name that we will be ssh'ing into the site with and ``address`` is the site address (ip or www).
