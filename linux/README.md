# Linux 基础命令
* `pwd` 查看当前所在路径
* `ls` 查看当前目录文件 `-a` 查看所有 `-l` 查看详细信息
* `cd` 切换目录 `j` jump 跳转目录模糊查询跳转`j wwwroo__`
* `rm` 删除文件不能删除文件夹 `rm -r` 删除所有 `rm -rf` 删除所有忽略提示
* `/`根目录 `~`家目录 `./`当前目录 `../`上级目录

# vim 基础命令

# git 操作
* 创建ssh `ssh -keygen -t rsa -b 4096 -C "MuzLingm@gmail.com(github邮箱)"`
* `git clone ssh path | https` 克隆远程git仓库
* `git remote -v` 查看记录的远程仓库地址

        git remote add origin git@github.com:muzlin/web-notes 把远程仓库地址加个标签=origin
        git remote add gitlab git@github.com:muzlin/linux.git 添加一个远程仓库的标签 gitlab
        git remote remove gitlab 删除gitlub的标签
        git remote set-url origin git@github.com:muzlin/update.git 修改ogigin标签对应的远程仓库地址
        git remote rename gitlab coding 修改gitlab标签为coding

* `git push origin master` 推送到远程仓库地址

        git push -f origin master 强制推送会覆盖别人的代码    
        git push gitlab master 推送到gitlab标签的地址上

* `git branch dev` 创建本地库dev分支

        git checkout dev 切换到dev分支
        git push origin dev 推送到origin地址的dev分支上
        git merge dev 合并dev分支
         
