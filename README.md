# gitalias
my git alias config

s = status
c = commit
b = branch
d = diff
co = checkout
ls = show --name-only
cat = show
l = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
alias = !git config --list |grep 'alias\\.'| sed 's/alias\\.\\([^=]*\\)=\\(.*\\)/\\1\\ => \\2/'| sort
