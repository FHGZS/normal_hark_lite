# normal_hark_lite


[![Build Status](http://nanshihui.github.io/public/status.svg)](http://nanshihui.github.io/2016/01/21/ToolForSpider%E7%AE%80%E4%BB%8B/) [![Python 2.6|2.7](http://nanshihui.github.io/public/python.svg)](https://www.python.org/) [![License](http://nanshihui.github.io/public/license.svg)](http://nanshihui.github.io/2016/01/21/ToolForSpider%E7%AE%80%E4%BB%8B/) 

通用的POC检测框架，有足够的POC，就可以找出相应的漏洞。
a farmework to test poc,based on search engine can get the valid infomation to test the vulnerability

##plugins文件夹说明
* 存放POC的位置
* 命名规则：component文件夹作为分类，针对具体的漏洞要独立建立一个文件夹，并在里面添加POC，里面已经有参考的模板了，使用的时候要继承T这个类，并实现相关函数

##使用方法
    python  __init__.py ip keywords
##截图
![Screenshot](http://nanshihui.github.io/public/normal_hack_lite.png)
* PS:if want to help with me to complete this project ...please fork it ^_^  
* 如果想用整合一起的可以参考该项目:[toolforspider](https://github.com/nanshihui/toolforspider)