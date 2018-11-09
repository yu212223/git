git config --global user.name "yu212223"
git config --global user.email "charlebround@163.com"

cd /a/b
git init

mkdir ~/.ssh
ssh-keygen -t rsa -b 4096 -C "charlebround@163.com"

https://github.com/settings/keys

add ssh key

ssh -T git@github.com

git remote add origin git@github.com:yu212223/git.git
git push -u origin master
