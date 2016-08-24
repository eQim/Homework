sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
npm config ls
mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
vim .profile
export PATH=-/.npm-global/bin:$PATH
:x
source ~/.profile
cd ~
mkdir homeWork5
cd homeWork5
git init
git checkout -b branch1
npm init
npm install gulp -D
npm install eslint -S
vim package.json //OK
sudo apt install git-extras
git-ignore node_modules
echo "node_modules/" >> .gitignore
git add package.json
git commit -a
git push npm branch1
git branch branch1 -d
eqm42@eQim:~/homeWork5$ git push npm :branch1
Username for 'https://github.com': eQim
Password for 'https://eQim@github.com': 
To https://github.com/eQim/npm
! [remote rejected] branch1 (refusing to delete the current branch: refs/heads/branch1)
error: не удалось отправить некоторые ссылки в «https://github.com/eQim/npm»
eqm42@eQim:~/homeWork5$

