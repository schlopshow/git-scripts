# Schlop's Git Automation Scripts

#Description:

These scripts currently perform the bare minimum. I recommend using an IDE that automates this process. My is plan to integrate these scripts with my terminal editor so that when I save and quit, it automatically prompts me for commit information, branch details, and pushes to my repository. I’m sure others have already created plugins for this purpose, but I want something that works with any editor and any terminal.

Collection of scripts created by Schlop to automate Git task via command line.

## Scripts Overview

### `existingrepo` Script
- The `existingrepo` script is used to link an **existing local Git repository** to a GitHub repository.

### `initrepo` Script
- The `initrepo` script is used for **initializing a new local Git repository** and pushing it to GitHub.

### `acp` Script
- The `acp` script is used for regular add . and commit message for peak **laziness** on all future pushes.
- This is basically what you use 99% of time

## Installation
This is in pseduo code because its up to you to determine where your $PATH variable, bascially just move them there and then you can use them by simply typing the name of the script.

```sh
git clone https://github.com/schlopshow/git-scripts.git
cd git-scripts
mv * ~/.local/bin
```
can the ```mv * ~/.local/bin``` command to whatever folder you use with your $PATH.

## TO-DOLIST

- I should add scripts for when you want to add only specific files, since doing add . doesn't work all the time, and might cause merge conflicts so you want a finer control.

## FIN
This is a work in progress. I will add more git automation scripts whenever I need them. If you want to contribute hmu at @schlopz on discord.
