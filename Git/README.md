# GIT Commands

## Introduction to git (version controling system)

1. use SSH during cloning a repo, cause if we use HTTPS then need to give username and password every time but if we use SSH only once we need to give the SSH public key in github
2. when we do pull, two types of work happen : fetch and merge
3. semantic versioning [eg: 2.0.1 here it represents like (major.minor.patch) way]
4. working tree means what i have in locally that i did not commit yet, working tree clean means there is nothing to commit in my local machine
5. every commit will generate a unique hash
6. switching branches changes files in your working directory, git resets your working directory to look like it did the last time you committed on that branch



## Commands

- `git --version`  [to see the current install version of git in your machine]
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
- `git commit -a -m "message"`  [will add/staged all unstaged files then will commit but be careful to use it]
- `git push`  [for pushing the commits in github/git servers]
- `git log -p commit_hash` [to see the changes in any particular commit]
- `git branch`  [to see the local branches]
- `git branch -r`  [to see the remote branches]
- `git push origin master`
- `mkdir x`  [for creating folder/directory named x in current directory]
- `git diff`
- `git diff --staged`
- `git diff --cached`
- `git init` [for locally using git without cloning any repo]
- `git add *.C`
- `git add LICENSE`
- `git commit -m 'Initial Project Version'`
- `git remote -v` [for seeing the remote branches]
- `git pull origin master`
- `git commit --amend -m "message"`  [for amending last commit(most recent commit only) with present changes, don't do ammend if you already pushed your commits]
- `git add --help`
- `git <command> --help`  [will show the details description of that command]
- `nano file_name`   [to open a file in the terminal, can edit also]
- `nano .gitignore`  [after that can add the files that i want to ignore while commiting in github]
- `cat .git/HEAD`  [we use 'cat' command to show(only no editing) something in the terminal, here .git/HEAD shows the current git head]
- `git branch b1`  [to create a new branch named b1]
- `git checkout b1` [to go from current branch to b1 branch]
- `git checkout -`  [to shift just previous branch]
- `git checkout -b b1` [create b1 branch and move there]
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
- `git fetch origin`  [will bring all remote changes in current working directory but won't merge]
- `git merge master`   [will merge]
- `git pull origin master`  [will bring & merge]
- `git push origin master` [wil go the local master branch changes to remote master branch]
- `git checkout --theirs --.`  [when conflict happens then to take theirs changes use this command]
- `git checkout --ours --.`  [when conflict happens then to take our/self changes use this command]
- `gitk`  [to see the git tree of current directory]
- `git rm PROJECTS.md`
- `git log -p -2`
- `git log --stat`
- `git log --oneline --decorate`  [to show where the branch pointers are pointing with also the commits with hash and commit message]
- `git log branch_name`  [to show the logs of that branch]
- `git log --all`  [to show the all logs of all branches]
- `git branch -v`  [to see the last commit on each branch]
- `git merge branch_name` 
- `git branch --merged`  [to see which branches are already merged into the branch you're on]
- `git branch --no-merged`  [to see all the branches that contain work you haven't yet merged in current branch]
- `git branch -d branch_name` [to delete a branch, if any work is there unmerged than git will ask you to confirm deletion by using -D instead -d]
- `git branch --merged branch_name`
- `git branch --no-merged branch_name`
- `git branch --move old_branch_name new_branch_name`
- `git push --set-upstream origin new_branch_name`
- `git push origin --delete old_branch_name`
- `git fetch origin`
- `git push origin branch_name`
- `git push <remote> <branch>`
- `git rebase master`  [to rebase current branch onto the master branch] [after doing this we can merge that branch with master branch by fast-forward marge]
- `git log --oneline`  [to show the commits with short hash and message]
- `pwd`
- `whereis go`
- `ls -la`
- `touch README.md`
- 


