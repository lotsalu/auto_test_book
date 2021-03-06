## Robot Framework
* 索引
* [1.安装](#1)
* [2.RIDE](#2)
* [3.RIDE Case 管理](#3)


>  
* Robot Framework是一个通用的关键字驱动自动化测试框架。测试用例以HTML，纯文本或TSV（制表符分隔的一系列值）文件存储。通过测试库中实现的关键字驱动被测软件。Robot Framework灵活且易于扩展。它非常适合测试有不同接口的复杂软件：用户接口、命令行，Web服务，专有的编程接口等。
* Robot Framework支持Python和Jython，推荐使用python2.7
*  使用pip 安装  

```dos
pip install robotframework
```
##<span id="1">安装</span>

需要先配置Python2.7,pip  
```dos
pip install framework
```
或者使用源码安装，切换到源码目录
```dos
python setup.py install
```
安装成功即可。

## <span id="2">RIDE </span>

> ** 官方介绍：** [RIDE](https://github.com/robotframework/RIDE) is a development environment for Robot Framework test cases.     
*   RIDE是Robot的第三方测试用例编辑器，可编辑用例，编辑关键字等并生成HTML，TXT等格式的文件。同时RIDE可直接可进行测试执行。RIDE是基于wxPython进行开发，所以安装RIDE前需要先行安装wxPython，其官方网站为：http://www.wxpython.org/。
*   这里推荐使用wxPython  Unicode 版本

 

** 安装RIDE **
```dos
pip install robotframework-ride
```
或者使用源码安装，切换到源码目录

```dos
python setup.py install
```

RIDE 可以做很多事情
##<span id="3">RIDE Case 管理</span>
首先是Project，如图  
<img src="pic/rf1.png" alt="GitHub" title="GitHub,Social Coding" width="400" height="200" />  
<img src="pic/rf2.png" alt="GitHub" title="GitHub,Social Coding" width="700" height="200" />



