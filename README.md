# sublime-text-3

This is my setup for Sublime Text 3.

Created following directions [here](https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d).

## Installation

In Sublime Text open packages folder (Preferences - Browse Packages):

```
$ git init
$ git remote add origin git@github.com:carlosescri/sublime-text-3.git
$ git fetch
$ git reset --hard origin/master
```

> With the last line, the existing setting files will be overwritten by those from the repository. If you want your local files to be committed, just make a backup before and copy the files back to the created repository to commit the changes. Or remove the “hard” flag of the reset instruction and merge all changes manually.

## Install Package Control

Visit [installation page](https://packagecontrol.io/installation) and follow instructions.