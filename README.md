## 前言

本项目是一个基于Java语言开发的新生宿舍管理系统，是一个适用于高校宿舍管理的实战项目。此项目采用了当前流行的Spring Boot框架、Vue前端技术，以及MySQL数据库，旨在实现简单、高效的宿舍管理功能。以下将详细介绍本项目的相关内容。

## 内容介绍

本项目主要实现了新生宿舍的基本管理功能，包括宿舍楼信息管理、房间信息管理、学生信息管理、宿舍分配与调整等。通过使用本项目，可以实现宿舍管理的规范化、数字化，提高工作效率。此外，本项目还提供了详细的源码、文档报告和代码讲解，方便学习和二次开发。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是本项目中的一个示例代码片段，展示了如何使用Spring Boot进行宿舍楼信息的查询：

```java
// 引入宿舍楼信息实体类和JPA相关依赖
import com.example.demo.entity.Dormitory;
import com.example.demo.repository.DormitoryRepository;

// 定义一个DormitoryController类
@RestController
@RequestMapping("/dormitory")
public class DormitoryController {

    // 注入DormitoryRepository
    @Autowired
    private DormitoryRepository dormitoryRepository;

    // 查询所有宿舍楼信息
    @GetMapping("/list")
    public List<Dormitory> listDormitory() {
        return dormitoryRepository.findAll();
    }
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/319806/22/24871/151528/689efc06Fb85eff56/1f3d6a457adf76de.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/310107/29/27013/14634/689efbe5F89bc7a2e/04711a2c57bd3f9d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/293693/17/11813/21208/689efbe6F8a36b9b8/933ce0a487535997.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325664/40/4971/104123/689efbe7Fba7b88b9/645409e5010e4ff8.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/291747/17/25532/18590/689efbe8Fafa2835d/da72a7f50977cfbe.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326489/21/4722/19340/689efbe7Fcf3508ed/7b2620b929fed2ce.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/315160/24/26932/108959/689efbe9F6a9e6e8f/e217c27b5eef3d26.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/307598/14/26408/18094/689efbeaF8601eb76/3311286478d875c7.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/295593/11/14045/20342/689efbeaFe2ebb37a/8fa255048314ede5.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320744/26/25214/30483/689efbebF09873113/0f4195c1b7a76276.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
