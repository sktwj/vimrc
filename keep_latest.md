git remote remove upstream
git remote add upstream git@github.com:amix/vimrc.git
git remote -v
git fetch upstream
git merge upstream/master
git pull origin master
git push 
