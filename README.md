# Git-Bash-Aliases
My custom git bash aliases to share across my machines. 

### Aliases
alias gd='git diff --color  sed s^color{#fff}{[^-+ ]}[−+ ]∗[-+ ]1  less -r'
alias glog="git log --graph --pretty=format'%Cred%h%Creset %an %s - %Creset %C(yellow)%d%Creset %Cgreen(%cr)%Creset' --abbrev-commit --date=relative"
alias gs='git status -sb'
alias ga='git add .'
alias gcm='git commit -am'
alias gl='git pull --prune'
alias gp='git push origin HEAD'

alias gco='git checkout'
alias gb='git branch'

alias e='code .'

### Follow this guide to implement the aliases (or another guide).
https://stackoverflow.com/questions/45569288/create-alias-git-bash-windows-10#:~:text=Create%20alias%20Git%20Bash%20Windows%2010.%201%20Open,bash%20terminal.%207%20check%20the%20alias%20command.%20
