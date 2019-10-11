Dans MTP:

Création de README.md

git add --all
git commit -m "first commit"

git branch front
git branch devOps

git checkout devOps
touch script.py
git add script.py
git commit -m "script.py"

git checkout front
touch index.html
mkdir css
touch css/style.css
git add --all
git commit -m "front"

git remote add origin https://github.com/ABentounes/TP1.git

git push origin front devOps

git checkout master
git merge devOps
git merge front

git push origin master

