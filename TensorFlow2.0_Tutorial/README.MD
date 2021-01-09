# TF2.x版本教程性质的代码xxxxx

- 由于一些敏感因素,因此之前GitHub的master主分支名称被换成了诸如main/root等等中性名词,因此要讲master分支切换为main分支的话, 步骤如下:
    1.1 背景： 本地当前分支为master，远程仓库为main，且远程仓库与本地仓库有 unrelated histories这样的问题，如远程仓库有README.md但本地没有；
    1.2 步骤：
        git checkout -b main
        git branch
        git merge master
        git pull origin main --allow-unrelated-histories
        git push origin main
    1.3 网址： https://blog.csdn.net/qq_42585582/article/details/109006783

- [知乎——如何上传本地代码到github]https://zhuanlan.zhihu.com/p/34625448

- [Git配置SSH Key的时候提示密钥无效]https://www.cnblogs.com/gosun/p/13044672.html

- [ubuntu使用git的时：Warning: Permanently added the RSA host key for IP address '13.250.177.223' to the list of known hosts.]https://www.cnblogs.com/yun6853992/p/9348540.html

- [mac git命令按Tab不能自动补全解决方法]https://blog.csdn.net/qq_43111384/article/details/104331312

- [git clone 速度慢的问题]https://www.cnblogs.com/cleves/p/13673312.html

- [git 推送更新出现错误： Updates were rejected because the remote contains work that you do]https://blog.csdn.net/gongqinglin/article/details/79752398