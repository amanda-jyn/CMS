# github问题集（二）
1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
>new repository新建仓库
>import repository导入仓库
>new gist 新建代码片段
>new organization 建立新组织
2. 如何能将仓库中的html文件直接解析成页面？
>在仓库setting中设置github pages中source改为master branch模式，保存。
3. 如何删除仓库
>打开仓库，在setting中最后danger zone中delete this repository，点击删除
4. Bash是什么操作系统的命令
>inux操作系统
5. Pwd是什么命令
>pwd是print working directory的缩写，打印当前工作目录（显示当前所在目录）
6. Cd是什么命令
>change directory改变目录
7. Echo是什么命令
>在命令行打印信息（打印输出）
8. 配置git用户名的命令
>git config --global user.name“李云霄”
9. 配置邮箱的命令
>git config --global user.email “”
10. 命令行换行方式
>/
11. 令行终结方式
>ctrl+c
12. 使用命令行比GUI方式有何优势
>命令行可以统一执行所有仓库的更改
>速度快
>开发容易
>命令行出现错误会提示错误在哪里，gui不会
>所有命令行有标准输入输出，但是gui没有
13. 提交到本地仓库时为什么有暂存区?
>对版本控制有意义，对提交的内容可分为不同区
>原材料入库，未检验或检验后有疑惑，待处理。
>成品入库，同上。
>要领出的东西比较多，为了节约时间，提前做好准备，放在暂存区。
>入库的库位一时没准备好，暂时放一下。
>正常检查过程中发现有疑问的物品，暂时放一下。
14. 新建代码仓库的命令
>git init
15. git clone [url] 这个命令的作用是
>得到一个项目的拷贝，url为地址
16. 加指定文件到暂存区的命令
>git add
17. 删除工作区文件，并且将这次删除放入暂存区的命令
>git rm
18. 改名文件，并且将这个改名文件放入暂存区的命令
>git mv
19. 提交暂存区到仓库的命令
>git commit
20. 直接从工作区提交到仓库的命令
>git commit -a -m
21. 显示变更信息的命令
>git statos
22. 查看历史信息的命令
>git log
23. Commit的意义是
>提交信息
24. Pull的意义是
取回远程主机某个分支的更新，再与本地仓库合并
25. Push的意义是
>将本地仓库和远程仓库合并，提交到远程仓库上
