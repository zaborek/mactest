# mactest

### A first lesson in github from Colin

1) make repo in github
2) clone via gitclone button with https (it is green) -- copy to clipboard
3) go to location in file system where you want to put the repo
4) type "git clone (paste https from git button here)"
5) enter credentials
6) establish .gitignore
7) ready to commit? type "git status"
8) type "git add ." period for all changes
9) type "git commit -m 'message'" avoid punc in message
10) type "git push" to upload

11) to refresh local machine with origin (github) type "git pull" in the correct git repo on your machine.

12) don't edit unless you're up to date


### Other things:

1) You  might want to edit the defualt text editor that git will use to edit files. To do this, type 'git config --global core.editor "emacs"' for emacs, or your editor of choice.

2) You may also want to update your name and email in the configuration. To do this type "git config --global --edit" to edit name and email (it will open in your default text editor).