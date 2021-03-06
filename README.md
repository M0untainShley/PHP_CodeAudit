### 项目说明

- 此项目用来记录自己学习PHP代码审计的分析过程，并且会附带源代码，如果能帮助到你，不胜荣幸^ ^

- 图片是存在的，因为国内的网络问题图片显示不出来，图片使用的相对路径，可以下载项目到本地进行复现或者阅读

  

#### 图片无法显示问题

Windows，打开hosts文件，添加一下内容即可

```cmf
151.101.184.133    assets-cdn.github.com
151.101.184.133    raw.githubusercontent.com
151.101.184.133    gist.githubusercontent.com
151.101.184.133    cloud.githubusercontent.com
151.101.184.133    camo.githubusercontent.com
```





### 环境

IDE：PhpStorm

PHP集成环境：PhpStudy，https://www.xp.cn/download.html

代码分析工具：Seay源代码审计系统，https://github.com/f1tz/cnseay



### 思维导图

<img src="./img/1.png">



### Web漏洞

#### SQL注入

[BlueCMS SQL 注入](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/1_SQL%20Injection/1_Bluecms/Bluecms%20SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md)



[淡然点亮图标系统 SQL注入](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/1_SQL%20Injection/2_sqqyw/%E6%B7%A1%E7%84%B6%E7%82%B9%E4%BA%AE%E5%9B%BE%E6%A0%87%E7%B3%BB%E7%BB%9F%20SQL%E6%B3%A8%E5%85%A5.md)



#### 文件安全

##### 文件包含

[MetInfo V4.0 文件包含漏洞](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/2_File%20Security/1_%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB/MetInfoV4.0%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB%E6%BC%8F%E6%B4%9E/MetInfoV4.0%E6%96%87%E4%BB%B6%E5%8C%85%E5%90%AB%E6%BC%8F%E6%B4%9E.md)



##### 文件下载/读取

[phpcms V9.6.1 任意文件读取](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/2_File%20Security/2_%E6%96%87%E4%BB%B6%E4%B8%8B%E8%BD%BD%26%E8%AF%BB%E5%8F%96/phpcmsV9.6.1%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96/phpcms9.6.1%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E.md)



##### 文件上传



##### 文件删除



#### 代码执行/RCE

[zzzphp代码执行漏洞](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/3_RCE/1_zzzphp/zzzphp%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md)



#### XSS

[骑士CMS 存储型XSS](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/4_XSS/1_74CMS%20%E5%AD%98%E5%82%A8%E5%9E%8BXSS/74%EF%BC%88%E9%AA%91%E5%A3%AB%EF%BC%89CMS%20%E5%AD%98%E5%82%A8%E5%9E%8BXSS%E6%BC%8F%E6%B4%9E.md)



#### CSRF

[DiscuzX 2.5 CSRF脱库](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/5_CSRF/1_DiscuzX2.5CSRF%E6%BC%8F%E6%B4%9E/DiscuzX_2.5_CSRF%E8%84%B1%E5%BA%93%E6%BC%8F%E6%B4%9E.md)



#### 命令执行



#### 变量覆盖

[变量覆盖漏洞](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/6_%E5%8F%98%E9%87%8F%E8%A6%86%E7%9B%96/%E5%8F%98%E9%87%8F%E8%A6%86%E7%9B%96%E6%BC%8F%E6%B4%9E.md)



#### 逻辑漏洞

[逻辑漏洞](https://github.com/M0untainShley/PHP_CodeAudit/blob/master/7_%E9%80%BB%E8%BE%91%E6%BC%8F%E6%B4%9E/%E9%80%BB%E8%BE%91%E6%BC%8F%E6%B4%9E.md)



#### 会话漏洞



#### 二次注入漏洞



#### 框架漏洞

可以参考此项目：https://github.com/Mochazz/ThinkPHP-Vuln
