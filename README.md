# 前言

欢迎来到基于微信小程序的在线学习系统SpringBoot项目。本项目致力于为用户提供一个便捷、高效的在线学习平台，通过微信小程序实现课程学习、进度跟踪等功能。以下是本项目的详细介绍。

# 内容介绍

本项目主要包括以下模块：课程展示、课程详情、学习进度跟踪、个人中心等。用户可以通过微信小程序浏览各类课程，查看课程详情，并根据自身需求进行学习。系统会自动记录用户的学习进度，便于用户随时了解自己的学习情况。同时，个人中心提供了完善的个人信息管理功能，让用户能够更好地掌控自己的学习过程。

# 技术介绍

## 语言：Java

## 使用框架：
- Spring
- Springmvc
- Mybatis
- 微信小程序

## 前端技术：
- JS
- Vue
- CSS3
- Uniapp

## 开发工具：
- IDEA/Eclipse
- Uniapp

## 数据库：
- MySQL 5.7/8.0

## 数据库管理工具：
- phpstudy/Navicat

## JDK版本：
- jdk1.8

## Maven：
- apache-maven 3.8.1-bin

## 前端环境：
- Node.Js 12\14\16

# 核心代码

以下是本项目中的一个核心代码片段，展示了如何通过Spring Boot接收前端请求并返回课程数据：

```java
@RestController
@RequestMapping("/course")
public class CourseController {

    @Autowired
    private CourseService courseService;

    @GetMapping("/list")
    public ResponseEntity<List<Course>> list() {
        List<Course> courseList = courseService.list();
        return ResponseEntity.ok(courseList);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/347865/25/3136/103671/68c5971bF86c23663/480d2a00a327e1e2.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327837/20/19659/25301/68c596f3F78e1a382/bfe317fc707eea1e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344470/9/2962/59685/68c596f3F405284b5/ee7bc4cbb8ae194d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332146/25/12995/24669/68c596f3Ffae8e6eb/c68ad776cc8850ac.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326600/23/19780/52499/68c596f3Fa09913ec/0a01e1fd53aeaa70.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/332734/32/12901/22948/68c596f4F8a337ecd/31212eaa4ce32272.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/334410/4/12870/20870/68c596f4F79e4ddb1/00c64343b674cfec.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/338798/5/10519/33252/68c596f4Fd224bfee/88390e048e7eb08a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/325479/24/19557/21122/68c596f4Fc0ed923e/9813518a67e9a0bb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/350762/19/3007/70531/68c596f4F1b29c7f7/2edca3f6c6667b3a.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
