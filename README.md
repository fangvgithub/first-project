# first-project
我的第一个项目
###git init
要对某个项目使用git进行管理，需要使用git init 命令初始化git仓库
git init会在当前目录生成一个隐藏文件夹.git
git 仓库会分成三个区
工作区：我们书写代码的地方，工作的目录就叫工作区
暂存区：暂时存储的区域，在git中，代码无法直接从工作区提交到仓库区，而是需要先从工作区添加到暂存区，然后才能从暂存区提交到仓库区。暂存区的目的是避免误操作。
本地仓库区：将保存在暂存区域的内容永久转存到git仓库中，生成版本号。生成版本号之后，就可以任意的回退到某一个具体的版本。

###git 配置
在第一次使用的时候，需要配置用户名邮箱和用户名称，这两条配置是很重要的，每次提交git代码时候都会引用这两条信息，记录是谁提交了代码，会永久的记录在历史记录中。
git config --global user.name "fangvgithub"
git config --global user.email "fangwei@itcast.cn"

git config --list 


