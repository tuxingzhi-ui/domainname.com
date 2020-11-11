---
title: 安装Nessus
author: 涂兴智
date: '2020-11-11'
slug: Nessus
categories:
  - Example
tags:
  - Markdown
---
## Nessus的安装
1.点击<http://www.tenable.com/products/nessus-home>,注册并填写可用邮箱拿到激活码。  
2.下载Nessus<https://www.tenable.com/downloads/nessus>,或者注册后邮件里面有下载链接🔗地址，直接点击即可。选择适合的版本进行下载。

3.安装完成后到浏览器访问<https://localhost:8834/ >，会进入到Nessus的欢迎和配置界面，从而激活和创建管理员用户，紧接着会加载插件。期间我不小心断网了，所以没下载成功，重新来一遍，保持网络通畅，下载结束后会编译。

4.全部结束后重启，Nessus服务重启命令
、、、
  - #主要是需要清楚命令所在路径
  - cd /Library/Nessus/run/sbin
  - sudo ./nessusd restart
、、、
## 初步使用
![](/2020-11-11-nessus/Nessus安装_files/Nessus（scan）.png)

![](/2020-11-11-nessus/Nessus安装_files/Nessus（主机扫描）.png)

**从而进行漏洞扫描**