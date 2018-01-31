# markdown 笔记

## 标题 Atx形式 行首插入 1 到 6 个 `#`
```
# 这是 H1

## 这是 H2

###### 这是 H6
```

## 区块引用 每行的最前面加上 >
1.每行的最前面加上 `>`
> 区块引用

2.段落可以只在第一行加`>`
>这是一个段落  
段落  
落  

3.区块引用可以嵌套
>
> > This is nested blockquote.
>
> Back to the first level.

4.引用的区块内也可以使用其他的 Markdown 语法
> ## 这是一个标题。
> 
> 1.   这是第一行列表项。
> 2.   这是第二行列表项。

## 列表
1.无序列表使用 `* or + or -`
```
* li1
_ li2
+ li3
```

2.有序列表使用数字加英文句点`1.`
```
1. li1
2. li2
```  

3.列表中用区块引用`>`需要缩进
```
* li1
	> 区块引用
```

4.列表中需要放置代码块则需要缩进两次（八个空格）

5.列表需要`.`则转义`\.`
```
* li \.
```

## 代码区块 4 个空格或是 1 个制表符
段落：

    代码区块

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

## 分隔线 三个以上的星号、减号、底线来建立一个分隔线
    ***
    ---
> ---

## 链接
1.链接外网
 
   链接文字都是用 [方括号]
    地址用(小括号)
    [文字](地址 "title")
    [百度](www.baidu.com "baidu.com")
[百度](www.baidu.com "baidu.com")

2.当前主机资源

    使用相对路径
    See my [About](/about/) page for details.







