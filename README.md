# simple-copy-path package

Adds copy project path and full path to editor and tab menus.

## Context Menu on Tab

![tab](https://raw.githubusercontent.com/jnwaletzko/atom-copy-project-path/master/tab-screenshot.png)

## Context Menu in Editor

![editor](https://raw.githubusercontent.com/jnwaletzko/atom-copy-project-path/master/editor-screenshot.png)

# Check changes with original package

meld . ~/.atom/packages/simple-copy-path

# "Upgrade" package in atom

rsync -v --exclude .git --delete -a . ~/.atom/packages/simple-copy-path
