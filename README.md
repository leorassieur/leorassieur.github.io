# leorassieur.github.io

Clone repository
cd to where directory should be located
git clone link_here

Push
git add -A
git commit -m "message"
git push

Configure username
git config --global user.name "name"
git config --global user.email "email@domain.com"

Pull
git pull

Quit "full-blown commit"
esc key then :wq

Create repository with same account (leo don't worry about this part it's not as important): 
git init directory_name
cd to inside, then gedit README
push repository (instructions given above)
then make repository on github without README

still inside directory,
git remote add origin https://github.com/usr/repo.git
git push origin
git push origin gh-pages
