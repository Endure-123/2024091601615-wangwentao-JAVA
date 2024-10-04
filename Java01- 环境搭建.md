# Java01- 环境搭建

## Task1.安装JDK

1. ##### *JDK（Java Development Kit）：java开发工具包*

2. ##### *JRE（Java Runtime Environment）：java运行环境*

3. ##### *JVM（Java Virtual Machine）：java虚拟机*

4. ##### *关系：JDK包含JRE包含JVM*

5. ##### *原因：编写的工具，环境，平台都有了，包能跑的*

   ---

   ## Task2.配置环境变量

1. ##### 详情见task2.png文件。原因：相当于系统自动寻路了，在添加的Path中直接找到位置

![task2](C:\Users\WANG\Desktop\java01\task2.png)

---

## Task3.编译和运行

![task3](C:\Users\WANG\Desktop\java01\task3.png)

##### 涉及文件:

- ###### HelloJava.java：java源文件，即你编写的文件

- ###### HelloJava.class：编译后产生的字节码文件。JVM在跑java时，运行的是HelloJava.class

  ---

  ## Task4.IDE的安装和使用

#### 入教VS Code，开源免费强无敌！！！

---

# PLUS CONTENT

## Task5.Github Flow工作流实践

##### .git/ 目录：隐藏目录，是Git仓库的核心

##### .git目放了啥：

>1.*hooks*
>
>2.*info*
>
>3.*logs*
>
>……
>
>![屏幕截图 2024](C:\Users\WANG\Desktop\屏幕截图 2024.png)
>
>> （一图胜千言）

##### fork和clone有什么区别，Pull Request和push有什么区别？

> fork权限低一些，只配复制一个仓库而不影响原始仓库，而clone则权限相对较高，能够将修改推送到远程仓库

> Pull Request中文即“拉取请求”，通常由对分支进行更改并希望将这些更改合并到另一个分支的开发人员创建。一旦更改得到审查和批准，拉取请求就可以合并到目标分支中，将更改合并到主代码库中。
>
> 而push即推送，是将你编写的东西从本地存储发送到远程仓库。

##### 什么是git冲突？冲突发生的条件是什么，有哪些操作会引发冲突？应该如何处理？

> git冲突：多人开发的时候，当两个及以上开发者对同一文件的同一部份进行修改，并将这些修改尝试合并到同一个分支上时，Git无法自动决定采用哪个版本的修改，从而产生的冲突。

> 多人协作开发、同时修改同一文件或合并分支时。

> 我不造啊，没人跟我“开发”:cry:

> maybe好好沟通？

## ~~后面我是真不会啊（太菜力），用git提交去也qwq~~

