# Bashrc aliases

```
alias gs="git status"
alias grom="git rebase origin/master -i"
alias grod="git rebase origin/develop -i"
alias gpf="git push origin HEAD --force"
alias gf="git fetch origin --prune"
# Delete all merged branches that aren't master, develop, or epic branches
alias gdm="git branch --merged | egrep -v \"(^\*|master|develop|epic/*)\" | xargs git branch -d"
```
