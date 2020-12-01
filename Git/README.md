# GIT Commands

## Introduction to git

1. use SSH during cloning a repo, cause if we use HTTPS then need to give username and password every time but if we use SSH only once we need to give the SSH public key in github
2. when we do pull, two types of work happen : fetch and merge



## Commands

- git log  [for viewing the commit history of a repo]
- cat "path of a file x"  [for printing the contents of file x in terminal]
- ls [for showing the files in current working directory]
- git config --list  [for showing all the configs]
- clear  [for restarting the terminal with current directory]
- fish  [to use helpul terminator]
- echo "hello world" > test.md  [created a file test.md in current directory with writing "hello world" there]
- open "path of a file x"  [for opening the file x]
- code . [for opening current directory in vs code from terminal]
- git status
- git add .
- git add -A
- git add <file>
- git commit -m "message"
- git push
- git log -p <commit hash> [to see the changes in any particular commit]
- git branch  [to see the local branches]
- git branch -r  [to see the remote branches]
- git push origin master
- mkdir x  [for creating file named x in currnt directory]
- git init [for locally using git without cloning any repo]
- git remote -v [for seeing the remote braches]
- git pull origin master
- git commit --amend -m "message"  [for amending last commit(most recent commit only) with present changes]
- git add --help
- git <command> --help
- nano file_name
- nano .gitignore  [after that can add the files that i want to ignore while commiting in github]
- cat .git/HEAD
- git branch b1
- git checkout b1
- git checkout -
- git checkout -b1 b1 [create b1 branch and move there]
- git branch -D b1 [to delete b1 branch]
- ctrl + z  [for getting out from a running command in terminal]
- git stash
- git stash save "message"
- git stash list
- git stash apply
- git stash apply stash@{index}
- git stash drop
- git stash drop stash@{index}
- git stash pop [will take lastl commit and delete it]
- git stash pop stash@{index}
- git cherry-pick <that commit hash which want to bring here>
- git cherry-pick C1 C3  [apply that C1 & C3 changes]
- git cherry-pick C1..C5 [apply a range of commits, C1 < C5, C1 not included]
- git cherry-pick C1^..C5  [C1 included]
- git revert <that commit hash which want to revert>
- git fetch origin
- git merge master
- git pull origin master
- git checkout --theirs --.
- git checkout --ours --.
- 