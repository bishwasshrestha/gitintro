git init : 
	Initialize a repo 

git remote add origin https://github.com/bishwasshrestha/SSS1.git :
	linking remote repo with local repo

git add . :
	files staged to push to remote repo

git commit -m "Repo setup" :
	commiting files to be pushed

vim .gitignore :
	listing files to be ignored while pushing to remote repo
  
git push -u origin master :
	pushing files to remote repo on master branch

git pull master
git pull remote master
git pull https://github.com/bishwasshrestha/SSS1.git :
	merging remote repo and local repo

git status :
	checking the files that are modified or staged

git merge origin/master --allow-unrelated-histories :
	merging two repo ignoring their commits

git clone https://github.com/mattpe/git-intro.git :
	cloning the repo
	
git remote set-url origin https://github.com/bishwasshrestha/gitintro.git :
	changing the remote origin point:

git push -u origin master :		
	pushing the repo to remote

