Git is a version control system
Git is free software

this is a helloworld mannual

git config user.name "nisak0503"
git config user.email "x@gmail"

git add readme.txt
git commit -m "wrote a readme file"



relate to the remote repository:
git remote add origin https://github.com/nisak0503/learngit.git

first push after relation above:
git push -u origin master

every time : git push origin master

did i write readme.txt~ >w< silly me



if you want to go back to last 
	git add      or
	git commit :
	git checkout --readme.txt
		1. in the temporary area with modification
			back to temporary area
		2.modified, not in the temporary area yet
			back to the last edition without modification



HEAD is the latest version

git reset HEAD readme.txt
	temporary to workspace



in contrast to git add, we have git rm after you did a rm operation


