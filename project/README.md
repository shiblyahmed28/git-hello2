Git Version Check	"git --version
git -v"
Git configuration	"git config --global user.name ""shiblyahmed28""
git config -global user.email ""shiblyahmed28@gmail.com"""
Show config	git config --list
Creating Git Folder	"mkdir myproject
cd myproject"
out from directory	cd ..
Initialize Git	git init
check status	git status
add file	git add <FILENAME.TYPE>
add multiple file	"git add --all
git add .
ait add -A"
git commit	git commit -m "<COMMENTt>"
git short status	git status --short
git add and commit	git commit -a -m "<COMMENT>"
git help	"git --help
git commit --help
git status -help"
git show all command	"git --all
git commit --help --all"
Show branch	git branch
create branch	git branch <BRANCH NAME>
Switch to branch	git checkout <BRANCH NAME>
check directory	dir
merge branch	git merge <BRANCH NAME>
delete branch	git branch -d <BRANCH NAME>
view commit history	git log
local to remote repo add	"git remote add origin <REPOSITORY LINK>
git push --set-upstream origin master"
git fetch to check with remote	"git fetch origin
git status"
view log/chnages	"git log origin/master
git diff origin/master"
pull from fetch and merge	"git fetch origin
git status
git diff origin/master
git merge origin/master"
pull from remote	git pull origin
push	git push origin
view all local and remote branch	"git branch -a
git chekout <NEW REMOTE BRANCH>
git pull"
view only remote branch	git branch -r
push local branch to remote	"git status
git add .
git commit -m ""TEXT""
git push origin update-index    /  git push origin <NEW LOCAL BRANCH>"
git remote branch check	 git branch --set-upstream-to=origin/<branch>
ssh key 	ssh-keygen -t rsa -b 4096 -C "shiblyahmed28@gmail.com"
	ssh-add /Users/user/.ssh/id_rsa
git branch code	git clone -v --branch=Humaira/qualificationEducationSearch git@gitlab.grp.sscl.tech:grp/erp/grp-web/hrm-web-v2.git
	git clone -v --branch=mem-web-Spectrum git@gitlab.grp.sscl.tech:grp/erp/grp-web/mem-web.git
	git clone -v --branch=bcc-bitbucket-master git@gitlab.grp.sscl.tech:grp/erp/grp-web/hrm-web-v2.git
	
	
see remotes	git remote -v
change name of origin	git remote rename origin upstream
	
revert	git revert HEAD --no-edit
revert by multiple stage	git revert HEAD~x
	
view log oneline	git log --oneline
revert	git revert HEAd --no-edit
reset	git reset <HASH>
	git reset HEAD~
	git reset --hard
