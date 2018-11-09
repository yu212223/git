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
git push -u origin master
