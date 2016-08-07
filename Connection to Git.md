sudo -s
apt-get install git
git config user.name //eQim
git.config user.email //artemverba@yahoo.com
touch .gitignore_global
vim .gitignore_global
git config --global core.excludesfile ~/.gitignore_global
git config core.excludesfile
git config --global help.autocorrect 1
git config --global merge.tool kdiff3
ssh-keygen -t rsa -b 4096 -C "artemverba@yahoo.com"
pbcopy < ~/.ssh/id_rsa.pub //doesn't work for Ubuntu
sudo apt-get install xclip -y
xclip -selection clipboard < ~/.ssh/id_rsa.pub
gpg --gen-key //GPGTools doesn't exist for for Ubuntu
RSA RSA
4096
0 //no expiry date
y
Ваше настоящее имя: Artem Verba
Адрес электронной почты: artemverba@yahoo.com
Комментарий: Hello World
Вы выбрали следующий ID пользователя:
    "Artem Verba (Hello World) <artemverba@yahoo.com>"
gpg --armor --export "key here"
