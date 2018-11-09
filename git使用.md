git config --global user.name "username"  
git config --global user.email "useremail"  

cd /a/b
git init

mkdir ~/.ssh
ssh-keygen -t rsa -b 4096 -C "useremail"

https://github.com/settings/keys

add ssh key

ssh -T git@github.com

git remote add origin git@github.com:repositories

git add 文件路径，用来将变动加到暂存区
git commit -m "信息"，用来正式提交变动，提交至 .git 仓库
git push -u origin master

git status -sb 显示当前所有文件的状态


