npm install -g bower
mkdir homeWork6
cd homeWork6
git init
bower init
bower install jquery -S
vim bower.json
:x
touch .gitignore
git add bower.json
vim .gitignore
:x
git add .gitignore
git commit -m "Bower"
git remote add origin https://github.com/eQim/bower.git
git push -u origin master
link: https://github.com/eQim/bower
