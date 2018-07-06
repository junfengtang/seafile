title: 搭建个人云盘，一键安装seafile
author: tangjunfeng
date: 2018-07-06 15:43:54
tags:
---
### 执行
```
wget https://raw.githubusercontent.com/helloxz/seafile/master/install_seafile.sh
```

```
chmod +x install_seafile.sh && ./install_seafile.sh
```
### 1.选择1进行安装


![upload successful](/images/pasted-1.png)
### 2.按下回车

![upload successful](/images/pasted-2.png)
### 3.起个名字，字母数字都可以

![upload successful](/images/pasted-3.png)
### 4.填入自己的 IP

![upload successful](/images/pasted-4.png)
### 5.可以一路回车(默认设置就好）

![upload successful](/images/pasted-5.png)
### 6.设置管理员

![upload successful](/images/pasted-6.png)

### 7.访问
打开 http://IP:8000
### 8.启动和停止服务
启动服务：/home/MyCloud/seafile-server/seafile.sh start
停止服务：/home/MyCloud/seafile-server/seafile.sh stop
### 9.卸载
chmod +x install_seafile.sh && ./install_seafile.sh
选择2选项即可
### 其他扩展安装
https://manual-cn.seafile.com/extension/webdav.html