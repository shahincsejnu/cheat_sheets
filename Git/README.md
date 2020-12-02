# GIT Commands

## Introduction to git

1. use SSH during cloning a repo, cause if we use HTTPS then need to give username and password every time but if we use SSH only once we need to give the SSH public key in github
2. when we do pull, two types of work happen : fetch and merge



## Commands

- `git log`  [for viewing the commit history of a repo]
- `cat path_of_a_file_x`  [for printing the contents of file x in terminal]
- `ls` [for showing the files in current working directory]
- `git config --list`  [for showing all the configs]
- `clear`  [for restarting the terminal with current directory]
- `fish`  [to use helpul terminator]
- `echo "hello world" > test.md`  [created a file test.md in current directory with writing "hello world" there]
- `open path_of_a_file_x`  [for opening the file x]
- `code .` [for opening current directory in vs code from terminal]
- `git status`  [for seeing the current status of git working tree]
- `git add .`   [for staging all the files]
- `git add *`   [for staging all the files except the files that started with dot(.)]
- `git add -A`  
- `git add file_name` [for staging specific file]  
- `git commit -m "message"`   [for commiting (snapshot)]
- `git push`  [for pushing the commits in github/git servers]
- `git log -p commit_hash` [to see the changes in any particular commit]
- `git branch`  [to see the local branches]
- `git branch -r`  [to see the remote branches]
- `git push origin master`
- `mkdir x`  [for creating folder/directory named x in currnt directory]
- `git init` [for locally using git without cloning any repo]
- `git remote -v` [for seeing the remote branches]
- `git pull origin master`
- `git commit --amend -m "message"`  [for amending last commit(most recent commit only) with present changes]
- `git add --help`
- `git <command> --help`  [will show the details description of that command]
- `nano file_name`   [to open a file in the terminal, can edit also]
- `nano .gitignore`  [after that can add the files that i want to ignore while commiting in github]
- `cat .git/HEAD`  [we use 'cat' command to show(only no editing) something in the terminal, here .git/HEAD shows the current git head]
- `git branch b1`  [to create a new branch named b1]
- `git checkout b1` [to go from current branch to b1 branch]
- `git checkout -`  [to shift just previous branch]
- `git checkout -b1` b1 [create b1 branch and move there]
- `git branch -D b1` [to delete b1 branch]
- `ctrl + z`  [for getting out from a running command in terminal]
- `git stash`  [for saving modified things before moving other branches]
- `git stash save "message"`  [same before just added message]
- `git stash list`  [seeing all previous stashed list]
- `git stash apply` [for adding all the stashed things]
- `git stash apply stash@{index}`  [for adding spacific stashed item]
- `git stash drop`  [for droping/deleting all stashed things]
- `git stash drop stash@{index}`  [for droping/deleting specific stashed item]
- `git stash pop` [will take last stashed item and delete it]
- `git stash pop stash@{index}`  [will take specific stash and delete it]
- `git cherry-pick <commit hash which want to bring here>`
- `git cherry-pick C1 C3`  [apply that C1 & C3 changes]
- `git cherry-pick C1..C5` [apply a range of commits, C1 < C5, C1 not included]
- `git cherry-pick C1^..C5`  [C1 included]
- `git revert <commit hash which want to revert>`
- `git fetch origin`
- `git merge master`
- `git pull origin master`
- `git checkout --theirs --.`  [when conflict happens to ]
- `git checkout --ours --.`  [when coflict happens to ]