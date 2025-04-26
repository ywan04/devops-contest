git init
git remote add origin https://github.com/ywan04/devops-contest.git
git push -u origin master
mkdir Task1
cd Task1/
ls
touch README.md
ls
echo "Short description" > README.md 
ls
vim README.md 
git add README.md 
git push
git status

git push
git branch dev
git checkout dev 
cd ..
ls
touch file.txt
git add file.txt 
git commit -m "text file"
git push
git branch ywan04-new_feature
git checkout ywan04-new_feature 
echo "new readme" > README.md
git add README.md 
ls
git commit -m "new readme"
git push
echo ".*" > .gitignore
vim .gitignore 
git add .gitignore 
vim .git
vim .gitignore 
git commit -m "gitignore"
git add .gitignore 
git add -f .gitignore 
git commit -m "gitignore"
git push
echo "some changes" >> README.md 
git add README.md 
git commit -m "some changes"
git push
man git
git reset
git statujs
git status
git log
git reset af87f78b5ad68e23b9bca54ec0eac49dada8223d
git status
git log
git log > log.txt
vim log.txt 
git branch -D
git branch -D ywan04-new_feature 
git checkout dev 
man git
git help checkout
git checkout -f dev 
git branch -D ywan04-new_feature 
ls
vim ~/.bash_history 
ls
git add git_commands.md 
git status
git commit -m "git commands i used"
git push 
git push origin --delete ywan04-new_feature
git push 
git push -f
git checkout master 
git add log.txt 
git commit -m "add log"
git push
git push -f
