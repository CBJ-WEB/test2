# test2
情况:有远程仓库。自己创建本地仓库或者有本地仓库，提交本地仓库的代码到远程仓库
1.初始化一个本地仓库（.git文件，默认是不可见的）
git init
2.关联本地仓库和远程仓库
git remote add origin https://github.com/CBJ-WEB/test2.git
3.在git的同级的路径下，添加代码。添加新变化的 代码到暂缓区
git add .
4.提交暂缓区的代码到本地仓库
git commit -m"xxxxx"
5.提交本地仓库的代码到关联的远程仓库
git push origin master
