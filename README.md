## 前端笔记

### ul li 使用场景
    .看起来很多，每个元素又差不多
***
### H5 页面结构利用
```
    <body>
        <header>
            <nav></nav>
        </header>
        <main>
            <section></section>
            <section></section>
            <section></section>
            <section></section>
        </main>
        <footer></footer>
    </body>   
```
***
### 行内元素设置float后变成块级元素
    行内元素 margin panding 无效
    块级有效
***
## Git相关

#### 忽略版本库
`.gitignore` 文件
```
# 此为注释 – 将被 Git 忽略
# 忽略所有 .a 结尾的文件
*.a
# 但 lib.a 除外
!lib.a
# 仅仅忽略项目根目录下的 TODO 文件，不包括 subdir/TODO
/TODO
# 忽略 build/ 目录下的所有文件
build/
# 会忽略 doc/notes.txt 但不包括 doc/server/arch.txt
doc/*.txt
# ignore all .txt files in the doc/ directory
doc/**/*.txt

作者：关玮琳linSir
链接：https://www.jianshu.com/p/fe76f2890a14
來源：简书
```

#### 移除版本管理
移除并删除仓库文件 `git rm ***`
移除不删除仓库文件 `git rm --cached ***`

#### Git命令别名
```
$ git config --global alias.co checkout # git config checkout = git config co
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
$ git config --global alias.last 'log -1 HEAD'
$ git config --global alias.unstage 'reset HEAD --' == $ git unstage fileA $ git reset HEAD fileA
```

作者：关玮琳linSir
链接：https://www.jianshu.com/p/fe76f2890a14
來源：简书
***
