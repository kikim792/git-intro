#### Find me at http://j.mp/sbma-git

### Git
* VCS: Version control system
  * Other examples: subversion, mercurial, cvs, etc
* SCM: Source control management
  * https://git-scm.com


### git config
```
# System wide
$ git config --global user.name 'John Doe'
$ git config --global user.email 'jdoe@example.com'


# Current project
$ git config user.name 'John Doe'
$ git config user.email 'jdoe@example.com'

```
git config is for other configurations as well.


### git init
Put the project folder under version control
```
# Inside the project folder
$ git init
```

### git clone
```
# git clone <repo> <folder>
$ git clone git@github.com:kikim792/git-intro.git sbma-git-intro
```

### git status
```
$ git status
```

### git add
```
$ git add <file>
# or
$ git add <folder>
# or add every new/changed file/folder
$ git add -A
```

### git reset
```
# Unstage file
$ git reset <file>
# Unstage everything
$ git reset
```

### .gitignore

### git diff
* Shows what has changed.

### git log
```
$ git log
$ git log --decorate
```

### git commit
```
$ git commit -m 'Example commit message'
```

### git pull

### git push

### git help
```
$ git help <command>
```

References
----------

* GUI git client
  * https://www.sourcetreeapp.com

* Git official site
  * https://git-scm.com

* Tutorial
  * https://www.atlassian.com/git

* Git cheat sheet
  * https://www.atlassian.com/dms/wac/images/landing/git/atlassian_git_cheatsheet.pdf

* Git Book
  * https://git-scm.com/book/en/v2
