# Update
这是我的GitPage仓库
![](https://qgt-style.oss-cn-hangzhou.aliyuncs.com/newcoursep4/g1/g1-2-2/tenor.gif)
三步：
	1. git   add
	2. git   commit
	3. git   push  
	
	
	
	git  add
	使用命令：git  add  -A               A (all)
	
	 git   commit
	使用命令： git  commit  -m "本次提交的修改的备注"
	新创建的文件必须要按照顺序进行提交，如果只是修改文件，并没有创建文件，也可以使用  git  commit  -am  "本次提交的修改的备注" 
	
	 git  commit  -am "本次提交的修改的备注" 来合并前面两个步骤。
	
	 git  push   分为以下几种情形：
	• 第一次提交到本分支    git  push  origin  master    origin是远程仓库的默认名称，master是我们的分支名称（主分支）2020.10.1后，GitHub默认的主分支名改为了main，因此在这个时间点以后创建仓库，对应的命令应该改为： git  push  origin  main
	绝大多数情况下我们一个工程只会绑定一个远程仓库，比如我们课程中的GitHub，但是Git是支持绑定多个远程仓库的，如果绑定了多个，比如同时绑定了GitHub和Gitee，那么此时origin要替换为相应的远程仓库名称。1 当你在其他分支进行提交时，master要替换为相应的分支名
	• 第 2~n次提交到本分支   git  push 
	• 提交到其他分支   一般会切换到相应的分支并进行提交。
若提交到b分支，则输入命令：  git  push origin b
