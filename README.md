## 前言

欢迎来到我们的教育培训微信小程序项目。本项目致力于为广大用户提供便捷、高效的教育培训服务，通过微信小程序实现线上学习，满足用户的学习需求。以下是本项目的详细介绍。

## 内容介绍

本项目主要包括课程展示、课程分类、在线学习、个人信息管理等模块。用户可以浏览不同类别的课程，选择感兴趣的课程进行学习，同时可以查看学习进度、成绩等个人信息。此外，我们还提供了课程推荐、热门课程等特色功能，帮助用户快速找到适合自己的课程。

## 技术介绍

### 语言：Java
### 使用框架：
- Spring
- Springmvc
- Mybatis
- 微信小程序

### 前端技术：
- JS
- Vue
- CSS3
- Uniapp

### 开发工具：
- IDEA/Eclipse
- Uniapp

### 数据库：
- MySQL 5.7/8.0

### 数据库管理工具：
- phpstudy/Navicat

### JDK版本：
- jdk1.8

### Maven：
- apache-maven 3.8.1-bin

### 前端环境：
- Node.Js 12\14\16

## 核心代码

以下是本项目中的一段核心代码，展示了课程列表的查询功能：

```java
// CourseService.java
public List<Course> findCourseListByCategoryId(Integer categoryId) {
    CourseExample example = new CourseExample();
    example.createCriteria().andCategoryIdEqualTo(categoryId);
    return courseMapper.selectByExample(example);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
