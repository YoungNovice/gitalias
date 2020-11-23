# gitalias
my git alias config

### 
> s = status
> c = commit
> b = branch
> d = diff
> co = checkout
> ls = show --name-only
> cat = show
> l = log --color --graph --date=format:'%Y-%m-%d %H:%M:%S' --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset %C(red)<%cd>%Creset' --abbrev-commit -15
> ll = log --color --graph --date=format:'%Y-%m-%d %H:%M:%S' --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset %C(red)<%cd>%Creset' --abbrev-commit
> alias = !git config --list |grep 'alias\\.'| sed 's/alias\\.\\([^=]*\\)=\\(.*\\)/\\1\\ => \\2/'| sort
