# Using git and github
- git init
- git add
- git reset (add cancel)
- git commit -m 'comment'
- git branch
- git push
- git pull

# push file
- git push -u origin master
# connect with git
- git remote add origin 'git address'
# push file second
- git push -u 'second ID' master
# second connet with git
- git remote add 'secondID' 'git address'
# conment update
- git commit --amend
# download to git
- git clone 'git address'
# delete branch
- git branch -d branch_name
# git remote info origin and all
- git remote show origin
- git remote -v
# git remote rename
- git remote rename 'bf_name' 'af_name'
# git remote delete
- git remote rm 'name'
# git log
- git log --stat (info line)
- git log -p -3 (recent 3)
- git log --pretty=oneline (show oneline)
- git log --pretty=format:"%h -> %an, %ar :%s" --graph(h-hashname, an-auther_name, ar-date, s-commit_message)
# git Archive
- git archive --format=zip master -o Master.zip
# git Rebase (Update, Delete commit)
- git rebase -i HEAD~3
