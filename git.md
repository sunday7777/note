## git note



|  操作  |  命令  |  示例  |  备注  |
|  ---- |  ---  |  ---   |  ---  |
|  安装git  |  https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496 |
|  配置git  |  git config --global user.name "你的姓名"  git config --global user.email "你的邮箱" |
|  让Git显示颜色，会让命令输出看起来更醒目  |  git config --global color.ui true  |
|  创建版本库（在当前文件夹创建版本库）  |  git init |
|  将文件提交到暂存区  |  git add "文件名"  |
|  将暂存区的所有内容提交到本地当前分支（本地）  |  git commit -m "版本内容介绍"  |
|  查看仓库的当前状态  |  git status  |
|  对比该文件已提交的版本和本地代码的区别  |  git diff "文件名"   |
|  版本提交的历史纪录  |  git log  |
|  从远处仓库克隆代码  |  git clone 项目地址  |
|  这个是远程仓库拉取数据到本地仓库  |  git pull  |
|  将本地代码提交到远程服务器  |  git push  |
|  查看本地分支 |  git branch  |
|  创建并切换指定分支 |  git checkout -b 分支名称  |
|  合并指定分支到当前分支 |  git merge 分支名称  |
|  查看本地和远程仓库的所有分支 |  git branch -a  |
|  获取远程服务器的指定分支 |  git pull <远程库名> <远程分支名>:<本地分支名>  |   取回远程库中的online分支，与本地的online分支进行merge，要写成：git pull origin online:online |


### git工作流程
1、git add .（后面有一个点，意思是将你本地所有修改了的文件添加到暂存区）  
2、git commit -m""(引号里面是你的介绍，就是你的这次的提交是什么内容，便于你以后查看，这个是将索引的当前内容与描述更改的用户和日志消息一起存储在新的提交中)  
3、git pull origin master 这是下拉代码，将远程最新的代码先跟你本地的代码合并一下，如果确定远程没有更新，可以不用这个，最好是每次都执行以下，完成之后打开代码查看有没有冲突，并解决，如果有冲突解决完成以后再次执行1跟2的操作  
4、git push origin master 将代码推至远程就可以了





