# Git 基础命令以及上传github流程及指令

git init  #初始化git本地仓库

git status  #查看本地仓库状态

git add  hello.text   #把修改的某个文件增加暂存区中

git commmit -m "第一次提交" hello.text   	#提交到本地仓库中，会有历史版本

git reset --hard  版本号    #切换历史版本

git reflog , git log 	#可以查看分支版本情况

git branch -v 		#查看分支信息

git branch 分支名字  	#在当前分支新建分支

git checkout 分支名字  		#切换分支

git merge 需要合并的分支名字  	#（要先切换到master分支上，然后才能用此命令合并）

git remote add 别名  					#github仓库网址   给仓库地址设置别名



git push 	别名 master 				#(将master分支上的代码上传到github仓库中)

## 每次进行推送本地仓库到远程仓库，都需要：

---------------------------------------------------

git add  hello.text   #把修改的某个文件增加暂存区中

git commit -m "第一次提交" hello.text   	#提交到本地仓库中，会有历史版本

---------------------------------------------

git  pull 	别名 	master      		#将远程仓库拉取到本地

git clone 	远程仓库网址				#克隆远程仓库地址（拉取代码，初始化本地库，创建别名）

