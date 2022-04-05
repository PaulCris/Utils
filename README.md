# **Util Git Aliases**

    git config --global alias.co checkout
    git config --global alias.ci commit
    git config --global alias.st status
    git config --global alias.br branch
    git config --global alias.amen 'commit --amend --no-edit'
    git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"
    git config --global alias.type 'cat-file -t'
    git config --global alias.dump 'cat-file -p'
    git config --global alias.hidden '!git ls-files -v | grep "^[a-z]"'
    git config --global alias.bs "for-each-ref --sort=committerdate refs/heads/ --format=' %(refname:short) %09 %(committerdate:short)'"
    git config --global alias.fd 'diff --name-only'
    git config --global alias.urlshow 'config --get remote.origin.url'
    git config --global alias.aliashow 'config --get-regexp alias'

    git aliashow
    
