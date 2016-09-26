## Robot Framework
* 目录
* [1.安装](##安装)
* [3.RIDE Case 管理](##RIDE Case 管理)
>  
* Robot Framework是一个通用的关键字驱动自动化测试框架。测试用例以HTML，纯文本或TSV（制表符分隔的一系列值）文件存储。通过测试库中实现的关键字驱动被测软件。Robot Framework灵活且易于扩展。它非常适合测试有不同接口的复杂软件：用户接口、命令行，Web服务，专有的编程接口等。
* Robot Framework支持Python和Jython，推荐使用python2.7
*  使用pip 安装  

```
pip install robotframework
```
##安装

需要先配置Python2.7,pip  
```
pip install framework
```
或者使用源码安装，切换到源码目录
```
python setup.py install
```
安装成功即可。

## RIDE
> ** 官方介绍：** [RIDE](https://github.com/robotframework/RIDE) is a development environment for Robot Framework test cases.     
*   RIDE是Robot的第三方测试用例编辑器，可编辑用例，编辑关键字等并生成HTML，TXT等格式的文件。同时RIDE可直接可进行测试执行。RIDE是基于wxPython进行开发，所以安装RIDE前需要先行安装wxPython，其官方网站为：http://www.wxpython.org/。
*   这里推荐使用wxPython  Unicode 版本

 

** 安装RIDE **
```
pip install robotframework-ride
```
或者使用源码安装，切换到源码目录

```
python setup.py install
```

RIDE 可以做很多事情
##RIDE Case 管理
