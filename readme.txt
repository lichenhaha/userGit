git init
git config user.name "someone"
git config user.email "someone@someplace.com"
git add *
git commit -m "some init msg"

git status

git reset --hard HEAD~1

git reflog   //查看使用的命令

git checkout -- filename	//没有提交到暂存区，使用这个命令回退
	
git reset HEAD filename  //当add进暂存区，使用这个命令可以回退