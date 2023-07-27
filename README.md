# Git Workflow

This repository is to demonstrate my various Git shortcuts as well as create a shared space for how others use Git. The following are found in my .gitconfig file.

1. 	commend = commit --amend --no-edit
1. 	force-push = !git push origin $(git symbolic-ref --short HEAD) -f
1. 	refresh = !git fetch upstream && git rebase upstream/main
1. 	update = !git add . && git commend && git force-push