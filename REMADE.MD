20222年9月28日，快速入门git分布式版本控制系统。
常用命令如下：
git init 初始化仓库
git status 显示目前工作目录的状态
touch 命令是新建
code 命令是编辑
git add 一般用来把有变化的文件加入待提交的暂缓区域（staging area）但对untracked files它具有双重功效，先将其加入到版本管理中（从untracked 变成 tracked），再加入staging area。
git commit 这个命令commit目前在staging area的任何文件变化到版本仓库，在实际执行前不会打开文本编辑器让我们commit message 也就是版本说明
新建了hello.py 和toady.py两个python程序源文件