# test2
情况:有远程仓库。自己创建本地仓库或者有本地仓库，提交本地仓库的代码到远程仓库
1.初始化一个本地仓库（.git文件，默认是不可见的）
git init
2.关联本地仓库和远程仓库
git remote add origin https://github.com/CBJ-WEB/test2.git
3.把关联的远程仓库的代码拉取到本地仓库（不管远程仓库没有代码，这样做能确保远程与本地的代码尽可能的保持一致）
git pull origin master
4.在git的同级的路径下，添加代码。添加新变化的 代码到暂缓区
git add .
5.提交暂缓区的代码到本地仓库
git commit -m"xxxxx"
6.提交本地仓库的代码到关联的远程仓库
git push origin master
