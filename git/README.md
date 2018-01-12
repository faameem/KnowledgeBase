# git Commands ([git workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)) #

Description | Command
-- | -- 
**_Init_** | 
To initialize a git repository | $ git init
To check status of repository - do this often | $ git status
**_Clone_**|
To clone to a specific folder | $ git clone <repo> <directory>
To cloning a specific tag | $ git clone -branch <tag> <repo>
To shallow clone | $ git clone -depth=1 <repo>
**_Working with Develop Branch_**|
To create a feature branch from develop branch| $ git checkout develop
 | $ git checkout -b develop_fm
To merge a feature branch to develop branch| $ git checkout develop
 | $ git merge develop_fm
**_Staging_** |
To stage file.txt | $ git add file.txt
To diff staged files | $ git diff --staged
To un-stage files | $ git reset file.txt
**_Commit_** |
To commit | $ git commit file.txt -m "commit file.txt"
To view commit history | $ git log
**_Local to Remote_** |
To add local repo to github server | $ git remote add origin https://somerepo
To check what remote | $ git remote
To check read/write shortnames | $ git remote -v
**_Remote to Local_** | 
To pull from remote to local (master) | $ git pull origin master
To diff most recent commit (HEAD pointer) | $ git diff HEAD
To revert back to last commit | $ git checkout -- file.txt
**_Branching_** | 
To create a branch | $ git branch feature_fm
To view branches | $ git branch
To switch to new branch | $ git checkout feature_fm
To remove files from disk and stage the removal | $ git rm file.txt
To commit branch changes | $ git commit -m "Removed file.txt"
To push local branch commits to remote origin | $ git push -u origin feature_fm
To merge master with local so no coflicts | $ git merge master
To switch to master | $ git checkout master
To merge branch changes to master branch | $ git merge feature_fm
To delete the branch | $ git branch -d feature_fm
To push to remote repository | $ git push -u origin master

















  
