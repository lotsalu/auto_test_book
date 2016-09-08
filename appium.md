# Appium
[Appium](https://github.com/appium/appium) 是一个移动测试框架，支持ios，android，firefox os，同时还支持H5混合应用。

** 目的：** 通过本文对于Appium，RobotFramework-appium结合的方法，可以方便搭建Appium自动化测试框架，Case编写简化。如果不关注原理，可以略过下面的Appium 项目&原理。
## Appium安装
Appium安装见[环境配置](环境配置.md)的Appium篇。
## Appium 项目&原理
** 官方介绍：**
<img src="appium.png" alt="GitHub" title="GitHub,Social Coding" width="750" height="400" />    
### 目前mobile自动化的方案
<img src="appium_2.png" alt="GitHub" title="GitHub,Social Coding" width="750" height="600" />    
### Appium的优点
* 跨架构，native	hybrid	webview
* 跨设备，android	ios	 ﬁrefox os
* 跨语言， java	 python	ruby	 nodejs	php
* 跨app,	 可以在多个app之间交互	 
* 不依赖源代码
* 不限制测试框架和平台	  

### Appium在Android上的架构
  <img src="appium_3.png" alt="GitHub" title="GitHub,Social Coding" width="900" height="600" />   

 bootstrap.jar在appium中是以jar包的形式存在的，它实际上是一个uiautomator写的case包，通过PC端的命令可以在手机端执行。
 ## Appium在IOS上的架构
 (这部分暂时没有展开，后续展开)
  <img src="appium_4.png" alt="GitHub" title="GitHub,Social Coding" width="900" height="600" />    
### Appium 代码例子  

<img src="appium_5.png" alt="GitHub" title="GitHub,Social Coding" width="900" height="600" />    
### 总结    

*  使用 WebDriver 封装App操作接口，通过HTTP API使多语言的客户端支持成为可能。
*  异步队列。根据业务需求，将大量操作请求，通过队列的形式逐步分发执行，防止压力过大。
*  稳定性稍显不足appium 脚本在运行时不十分稳定。
*  代码不够清晰、简洁工程模块非常多，但是组织不够清晰，代码编写不够简洁。
*  多机支持不够简单one server To one client 架构导致多设备支持略麻烦。

## RobotFramework+Appium 
** 官方介绍：**
* AppiumLibrary is an appium testing library for RobotFramework.
* It uses Appium (version 1.x) to communicate with Android and iOS application similar to how Selenium WebDriver talks to web browser.
AppiumLibrary is modeled after (and forked from) appiumandroidlibrary, but re-implemented to use appium 1.X technologies.
* It support Python 2.x only.
