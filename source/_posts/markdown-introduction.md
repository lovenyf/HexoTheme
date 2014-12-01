title: markdown 语法简介
date: 2014-11-18 23:02:47
tags: markdown
---

## 题外话

之前试用了几种 github 上静态博客框架，最后还是选择了 hexo，由于其依赖于 node.js 相对于前端开发来说较为熟悉，所以便使用了 hexo 框架。

之前也未曾使用过Markdown，这边主要简单的学习介绍一下关于 Markdown 语法。Markdown 语法的目标主要是成为一种适用于网络的书写语言，而却并不是用来取代 html，语法种类较少，仅仅是为了网络中的易读易写。本文主要用来标记常用的 Markdown 语法，以及测试调整一下所采用主题的样式二次开发修改一下。

## Markdown 语法说明

**1\. p 标签：** 段落其实尤为简单，不需要一般格式，直接书写便是一个段落。

    这个是段落

实例：

这个是段落

**2\. br 标签：**仅仅需要一个回车符号。

    像这样这后面为回车
    到这里

实例：

像这样这后面为回车
到这里

**3\. h1，h2 等标题：** 文字前带n个 # 即可，或者文字下方为‘======’或‘------’代表h1和h2。

    #标题1
    #标题1#
    ##标题2
    ###标题3
    标题1
    =========
    标题2
    ---------------

实例：

#标题1#
##标题2

标题1
=========
标题2
---------------

**4\. blockquote 区块的引用：**整一段文本前或者每一行加上> 即可。

    >这里是blockquote内容这里是blockquote内容这里是blockquote内容
    >这里是blockquote内容这里是blockquote内容这里是blockquote内容

    >这里是blockquote内容这里是blockquote内容这里是blockquote内容这里是blockquote内容这里是blockquote内容这里是blockquote内容这里是blockquote内容

实例：

>这里是blockquote内容这里是blockquote内容这里是blockquote内容
>这里是blockquote内容这里是blockquote内容这里是blockquote内容

**5\. ul，ol 列表：**无序列表使用星号，加号或者减号作为列表标记，有序列表使用数字接英文句号。当然需要注意的是，在数字后跟随英文点号的需要使用 \. 来转义一下。

    * Large
    * Middle
    * Small

    + Large
    + Middle
    + Small

    - Large
    - Middle
    - Small

    1. Large
    2. Middle
    3. Small

实例：

* Large
* Middle
* Small

1. Large
2. Middle
3. Small

**6\. 代码区块：**在MD中建立代码区块很简单，只需要前面加入4个空格，或者1个制表符即可。记得块的上下需要有一行空行。

**7\. hr 分割线：**在一行中使用3个以上的星号，减号，底线来建立分割线，一行内不可以有其他的符号，中间可以有空格。

    * * *
    *****
    - - -
    -------
    ________

实例：

************

**8\. a 标签链接：**具有行内式和参考式两种，只用方括号标记。

    行内式：这里接下来有个链接[baidu](http://www.baidu.com 'title的值')。


实例：

行内式：这里接下来有个链接[baidu](http://www.baidu.com 'title的值')。

**9\. strong，em 强调标签：**使用一个星号或者底线号包围生产 em 标签，两个则生成 strong 标签

    *这里是em*
    _这里是em_
    **这里是em**
    __这里是em__

实例：

*这里是em*
_这里是em_
**这里是em**
__这里是em__

**10\. code 标记一小段行内代码：**使用 ` 包围起来即可。

    内容内容`asdfghjkl`容

实例：

内容内容`asdfghjkl`容

**11\. img 图片标签：**感叹号+方括号+地址。

    ![img](https://avatars0.githubusercontent.com/u/2505831)

实例：

![img](https://avatars0.githubusercontent.com/u/2505831)


**12\. 以下符号属于MD的标识符，需要使用反斜杠来进行转移一下。**

    \\ \` \* \_ \{ \} \[ \] \( \) \# \+ \_ \. \!

实例：

\\ \` \* \_ \{ \} \[ \] \( \) \# \+ \_ \. \!