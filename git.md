*git软件的学习

**git安装

git config --global user.name "jhh"

git config --global user.email "276876847@qq.com"

**创建git仓库

git init

git add git.md

git commit -m "commit git.md"

git diff git.md

git status

git log

git log --pretty=oneline

git reset --hard HEAD^

git reset --hard 2f7e660

git reflog

git checkout --file 把工作区的文件状态回退到暂存区的状态一致

git resetHEAD filename 回退暂存区的文件状态

git rm fileName 

ssh-keygen -t rsa -C "276876847@qq.com"

git remote add github git@github.com:276876847/git.git

git remote -v

git remote rm github

git push -u origin master

git push origin master











