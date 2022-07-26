git config
git init
git rm --cached <filename>
git status
git add <filename>
git add .
git commit -m "message"
git commit -a -m "commit message"
git commit --amend --no-edit
git commit --amend -m "update messaget"
git reset --soft HEAD^
git reset --hard HEAD^
git log
git log --pretty=format:"%h - %an, %ar - %s"
git checkout <commit-hash>
git checkout master
git branch <new-branch-name>
git checkout <new-branch-name>
git checkout -b <new-branch-name>
git branch
git branch -v
git merge master
