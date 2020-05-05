Git
===

## Proxy

`git config --local http.proxy http://<user>:<pwd>@<ip>:<port>`

## Change author on local commit

`git commit --amend --author="name <email>"`

## Change user for repository only

    git config --local user.name <name>

    git config --local user.email <email>


## Create new branch from remote

`git checkout -t <remote>/<branch>`

## Configure Beyond Compare

    diff.tool=bc
    difftool.bc.path=C:\Program Files\Beyond Compare 4\BCompare.exe
    merge.tool=bc
    mergetool.bc.path=C:\Program Files\Beyond Compare 4\BCompare.exe

## Move branch to SHA

`git branch -f <branch> <sha>`

## Subrepo

### Switch to a remote branch

`git subrepo clone <repository> <directory> --force --branch=[branch|tag]`

## Patch

### Apply

`git apply <filename>.patch`

### From staged changes

`git diff > <filename>.patch`

### From unstaged and staged changes

`git diff --cached > <filename>.patch`
