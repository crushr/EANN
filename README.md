## github上传步骤
### git init //初始化本地仓库
### git add *  //加入所有项目
### git commit -m "first commit"//提交到要地仓库，并写一些注释
### git remote add origin git@github.com:youname/Test.git //连接远程仓库并建别名：origin
### git push -u origin master //将本地仓库的东西提交到地址是origin的地址，master分支下

## 本地库自己改动后，删除github上的文件以进行同步
### git commit -a -m .
### git push

## 远程库自己改动或本地库改动导致本地库落后于远程库，因为不同步可能无法正常push，需要先pull进行同步后再push
### git pull --rebase origin master
