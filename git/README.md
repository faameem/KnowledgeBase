# git Commands #

Description | Command
-- | -- 
To initialize a git repository | $ git init
To check status of repository - do this often | $ git status
To stage file.txt | $ git add file.txt
To diff staged files | $ git diff --staged
To un-stage files | $ git reset file.txt
To commit | $ git commit file.txt -m "commit file.txt"
To view commit history | $ git log
To add local repo to github server | $ git remote add origin https://somerepo
To push local default branch master commits to remote origin | $ git push -u origin master
To pull from remote to local (master) | $ git pull origin master
To diff most recent commit (HEAD pointer) | $ git diff HEAD
To revert back to last commit | $ git checkout -- file.txt
To create a branch | $ git branch feature_fm
To view branches | $ git branch
To switch to new branch | $ git checkout feature_fm
To remove files from disk and stage the removal | $ git rm file.txt
To commit branch changes | $ git commit -m "Removed file.txt"
To switch to master | $ git checkout master
To merge branch changes to master branch | $ git merge feature_fm
To delete the branch | $ git branch -d feature_fm
To push to remote repository | $ git push

















  
