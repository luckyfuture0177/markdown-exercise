# markdown-exercise
练习一下readme的基本写作方法  
markdown语法练习
====
横线
---------
/***，---，___可以显示横线效果
***
---
___
标题
---
根据#号的多少   
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
####### 七级标题 ~~（没有了）~~  

二.字体
---
### · 加粗
要加粗的文字左右分别用两个*号包围  
**加粗文字**  
### · 斜体
要倾斜的文字左右用一个*号包围  
*倾斜文字*
### · 斜体加粗
要倾斜并加粗的文字用三个*号包围  
***斜体加粗***
### · 删除线
要加删除线的文字用两个~~号包围  
~~删除线~~  

三.引用
-----
在引用文字前加>即可  
>这是引用内容            
>>>>>>>可以嵌套，但是没什么用 --鲁迅

四.分割线
----
三个或三个以上的-或*都可以

---
***

五.图片
---
~~~
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
~~~
![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")

六.超链接
---
~~~
[超链接名](超链接地址 "超链接title")
title可加可不加
~~~
示例：  
~~~
[简书](http://jianshu.com)
[百度](http://baidu.com)
~~~
[简书](http://jianshu.com)  
[百度](http://baidu.com)

七.列表
---
### · 无序列表
~~~
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格
~~~
- 列表内容  

### · 有序列表
~~~
数字加点
1.列表内容
2.列表内容
3.列表内容  
注意：序号跟内容之间要有空格
~~~
### · 列表嵌套
上一级和下一级之间敲三个空格即可

八.表格
---
~~~
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
~~~

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟

九.代码
---
单行代码 用一个反引号包起来  
`daima`  
代码块 代码之间分别用三个反引号包起来，且两边的反引号单独占一行
```
def fun()
    print('这是一个十分nb的代码')
    ....
    ...
```

***
**以上，markdown的基本用法**

