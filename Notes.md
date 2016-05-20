#Python实战：四周实现爬虫系统
**xiaozhenliu via [网易云课堂](http://study.163.com/course/courseLearn.htm?courseId=1002794001)**

**本文件仅供个人学习交流，不得用于非法用途。**

##Week 1 

###1-1 网页的构成

[我的 1-1 作业代码](https://github.com/xiaozhenliu/python_4_weeks/blob/master/week1/1_1/1_1answer_of_homework/homework.html)

####构成：
- Html: 结构
- CSS: 样式

####HTML标记：
- `<head></head>` 给浏览器看的内容
  - `<meta>` 属性，包括字符集等
  - `<title></title>` 网页标题，显示在导航栏
  - `<link>` 可用于引用CSS样式
- `<body></body>` 在网页上显示的内容
  - `<div class="header"></div>` (或"main-content","footer"，对应CSS样式中的类别)
  - `<img src="" width="" height="" alt="">` 图片
  - `<a href=""></a>` 超链接
  - `<ul></ul>` 无序列表，用`<li></li>`标记列表中的每一项
  - `<h2></h2>` 小标题
  - `<hr>` 分割线，只有开始标签，没有结束标签
  - `<p></p>`段落

###1-2 网页元素解析

Task: 学会筛选出所有评分大于3的文章，展现标题和对应的分类

第1步：使用 BeautifulSoup 解析网页
第2步：描述要爬取的东西在哪
第3步：从标签中获得你要的信息

`Soup = BeautifulSoup(html,'lxml')`

(其他库：

- html.parser
- lxml HTML
- lxml XML 
- html5lib)









###1-3 真实世界中的网页元素解析
###1-4 网页中的动态信息
###第一周实战作业