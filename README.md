# gitalias
my git alias config

###
> s = status -s 
> ss = status
> c = commit
> b = branch
> d = diff
> co = checkout
> ls = show --name-only
> cat = show
> l = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset --abbrev-commit -15
> ld = log --color --graph --date=format:'%Y-%m-%d %H:%M:%S' --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit -15
> ll = log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset %C(red)<%cd>%Creset' --abbrev-commit
> lld = log --color --graph --date=format:'%Y-%m-%d %H:%M:%S' --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset %C(red)<%cd>%Creset' --abbrev-commit
> alias = !git config --list |grep 'alias\\.'| sed 's/alias\\.\\([^=]*\\)=\\(.*\\)/\\1\\ => \\2/'| sort
