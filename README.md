# 2022年夏季《移动软件开发》实验报告



<center>姓名：叶鹏  学号：20020007095</center>

| 姓名和学号         | 叶鹏，20020007095                                            |
| ------------------ | ------------------------------------------------------------ |
| 本实验属于哪门课程 | 中国海洋大学22夏《移动软件开发》                             |
| 实验名称           | 实验1：第一个微信小程序                                      |
| 博客地址           | [Click me if you can](www.existoT01.top)                     |
| Github仓库地址     | [You won't miss that](https://github.com/ExistoT01/mobileSoftwareDesign-lab1) |

（备注：将实验报告发布在博客、代码公开至 github 是 **加分项**，不是必须做的）



## **一、实验目标**

1、学习使用快速启动模板创建小程序的方法；2、学习不使用模板手动创建小程序的方法。



## 二、实验步骤

列出实验的关键步骤、代码解析、截图。

1. 创建项目

   <img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817201107150.png" alt="image-20220817201107150" style="zoom:80%;" />

2. 视图设计

   进行页面布局设计

   <img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817201157807.png" alt="image-20220817201157807" style="zoom:80%;" />

3. 逻辑实现

   【注意】：微信已更新获取用户信息的api，现在使用`wx.getUserProfile`方法

   <img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817202218275.png" alt="image-20220817202218275" style="zoom:80%;" />

   获取到用户信息以后，动态设置`name`与`image`元素，实现目的效果



## 三、程序运行结果

列出程序的最终运行结果及截图。

【点击前】

<img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817202337620.png" alt="image-20220817202337620" style="zoom:80%;" />

【点击】

<img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817202353151.png" alt="image-20220817202353151" style="zoom:80%;" />

【点击后】

<img src="C:\Users\ASUS\AppData\Roaming\Typora\typora-user-images\image-20220817202407200.png" alt="image-20220817202407200" style="zoom:80%;" />

## 四、问题总结与体会

描述实验过程中所遇到的问题，以及是如何解决的。有哪些收获和体会，对于课程的安排有哪些建议。

-----------

由于微信小程序社区更新换代频率很高，一些古早得教程并不适用，需要与时俱进的新的教材与教程，希望能提供一些可以使用在生活当中的课程。