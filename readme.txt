Git is a version control system.
Git is free software.
git config --global user.name 'Viccsen'
git config --global user.email 'lianghaung.vic@gmail.com'
git init 
git add <filename>
git commit -m 'somenotes'
git reset --hard HEAD^ <~100>
git reflog
git log --
git status
git diff
git reset --hard commit_id
stage(index)
git checkout -- filename
git reset HEAD filename
git rm
git push -u origin master
git push origin master
git remote add origin git@github.com:viccsen/firstRepository.git
git clone git@github.com:viccsen/xxx.git
git checkout -b dev == git branch dev  git checkout dev
git branch
git merge dev 
git branch -d dev
git log --graph 
git log --graph --pretty=oneline --abbrev-commit
//create some new merge now
git merge --no-ff -m 'merge with no-ff' dev
//create some new merge
//make some change
git stash
git stash list
git stash apply + git stash drop === git stash pop ?
git branch -D dev
git pull
git push origin branch-name
git branch --set-upstream branch-name origin/branch-name
git remote -v
git tag v1.0
git tag
git tag v0.9 commit_id
git show tagname
git tag -a <tagname> -m "blablabla..."
git tag -d v0.1
git push origin v2.0
git push origin --tags
git push origin :refs/tags/<tagname>可以删除一个远程标签