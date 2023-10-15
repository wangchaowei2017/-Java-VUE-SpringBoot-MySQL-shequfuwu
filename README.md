# 基于Java-VUE-SpringBoot-MySQL的社区服务管理系统-毕业设计

------------

![登陆界面](https://skywalking.pro/download/images/cell-platform/WX20230410-104027@2x.png "登陆界面.png")

####  **功能设计图** 
![功能设计图](https://skywalking.pro/download/images/cell-platform/WechatIMG1262.jpeg "功能设计图.png")

####  **联系作者** 

![联系作者](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/main-platform-wcw778899bb.png "联系作者.png")

**这是作者的微信二维码，如需本项目源代码，可扫码或者VX:wcw778899bb联系作者。**  



**系统功能持续更新中。。。**
#### 介绍
 **这是一个基于SpringBoot2.X VUE2.6 Antd1.7.2  MyBatisPlus Shiro1.5.0 Java1.8 实现的具备系统管理、权限管理、用户注册、缴费信息管理、资讯信息管理、维修信息管理、停车位信息管理、居民说信息管理、居民信息管理的多功能的社区服务管理系统， 可作为商用、毕业设计项目、快速开发模版项目、特别是社区管理的系统。** 
#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
|  权限框架 | 作者自定的的权限相关框架  | 可以控制到按钮权限  |
| Antd1.7.2 |  阿里出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |
#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")
#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。
### 联系作者
#### 微信号: SkywalkingPro
#### 系统演示地址:
```
登录地址: https://www.skywalking.pro/cell-platform
登录账号: admin
登录密码: 123456
```
**若演示地址不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。

**下图为系统前后端分离的软件架构图**
![软件架构图](https://www.skywalking.pro/download/images/cell-platform/WechatIMG226.jpeg "软件架构图")

#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. 作者封装的权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图](https://skywalking.pro/download/images/cell-platform/WX20230410-105221@2x.png "系统技术文档截图.png")

### 项目代码展示

#### 前端VUE代码截图展示

![前端VUE代码截图展示](https://skywalking.pro/download/images/cell-platform/WX20230410-105320@2x.png "前端VUE代码截图展示.png")

#### 后端Java代码截图展示

![后端Java代码截图展示](https://skywalking.pro/download/images/cell-platform/WX20230410-114420@2x.png "后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://skywalking.pro/download/images/cell-platform/WX20230410-114500@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://skywalking.pro/download/images/cell-platform/WX20230410-104027@2x.png "登陆界面.png")

#### 系统管理模块

- 系统主页

![系统主页](https://skywalking.pro/download/images/cell-platform/WX20230410-140422@2x.png "系统主页.png")

- 菜单管理

![菜单列表](https://skywalking.pro/download/images/cell-platform/WX20230410-140546@2x.png "菜单列表.png")

![菜单新增](https://skywalking.pro/download/images/cell-platform/WX20230410-140624@2x.png "菜单新增.png")

- 角色管理

![角色管理](https://skywalking.pro/download/images/cell-platform/WX20230410-140652@2x.png "角色管理.png")

- 系统用户管理

![系统用户](https://skywalking.pro/download/images/cell-platform/WX20230410-140729@2x.png "系统用户.png")

![系统用户编辑](https://skywalking.pro/download/images/cell-platform/WX20230410-140801@2x.png "系统用户编辑.png")

#### 系统监控模块

- 系统日志

![系统日志](https://skywalking.pro/download/images/cell-platform/WX20230410-140836@2x.png "系统日志.png")

#### 业务模块

- 缴费管理

![缴费管理](https://skywalking.pro/download/images/cell-platform/WX20230410-140921@2x.png
 "缴费管理")

- 资讯信息管理

![资讯信息管理](https://skywalking.pro/download/images/cell-platform/WX20230410-141024@2x.png
 "资讯信息管理")

 ![资讯信息新增](https://skywalking.pro/download/images/cell-platform/WX20230410-141056@2x.png
 "资讯信息新增")

- 维修信息管理

![维修信息管理](https://skywalking.pro/download/images/cell-platform/WX20230410-141145@2x.png
 "维修信息管理")

 ![维修提交](https://skywalking.pro/download/images/cell-platform/WX20230410-141218@2x.png
 "维修提交")

- 停车位管理

![停车位管理](https://skywalking.pro/download/images/cell-platform/WX20230410-141304@2x.png "停车位管理.png")

![停车位新增](https://skywalking.pro/download/images/cell-platform/WX20230410-141335@2x.png "停车位新增.png")

- 居民说信息管理

![居民说信息管理](https://skywalking.pro/download/images/cell-platform/WX20230410-141432@2x.png "居民说信息管理.png")

![居民说信息新增](https://skywalking.pro/download/images/cell-platform/WX20230410-141517@2x.png "居民说信息新增.png")

- 居民信息管理

![居民信息管理](https://skywalking.pro/download/images/cell-platform/WX20230410-141551@2x.png "居民信息管理.png")

![居民信息新增](https://skywalking.pro/download/images/cell-platform/WX20230410-141734@2x.png "居民信息新增.png")

#### 系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统统计图表
    * 系统访问量统计
    + 系统模块导航
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
+ 缴费信息管理
  - 缴费信息管理
    * 缴费信息条件查询
    + 缴费信息新增
	* 缴费信息修改
    + 缴费信息批量删除
	+ 缴费信息单个删除
+ 资讯信息管理
  - 资讯信息管理
    * 资讯信息条件查询
    + 资讯信息新增
	* 资讯信息修改
    + 资讯信息批量删除
	+ 资讯信息单个删除
+ 维修信息管理
  -  维修信息管理
    *  维修信息条件查询
    +  维修信息新增
	*  维修信息修改
    + 维修信息批量删除
	+ 维修信息单个删除
+ 停车位信息管理
  - 停车位信息管理
    * 停车位信息条件查询
    + 停车位信息新增
	* 停车位信息修改
    + 停车位信息批量删除
	+ 停车位信息单个删除
+ 居民说信息管理
  - 居民说信息管理
    * 居民说信息条件查询
    + 居民说信息新增
	* 居民说信息修改
    + 居民说信息批量删除
	+ 居民说信息单个删除
+ 居民信息管理
  - 居民信息信息管理
    * 居民信息条件查询
    + 居民信息新增
	* 居民信息修改
    + 居民信息批量删除
	+ 居民信息单个删除
	
#### 演示地址
```
登录地址: https://www.skywalking.pro/cell-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言



#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf cell-platform-api.tar.gz (解压tar包)
3.  cd cell-platform-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
