---
layout: post
category: "docker"
title:  "Docker脚本安装"
tags: [docker]
---
#### curl -fsSL [https://get.docker.com](https://get.docker.com) \|sudo sh
#### 安装成功后会告知用户如何使用非root权限操作Docker。
```
If you would like to use Docker as a non-root user, you should now consider
adding your user to the “docker” group with something like:
sudo usermod -aG docker $your_user
Remember that you will have to log out and back in for this to take effect!
```
将docker.socket访问权限设置为660将其所属用户组设为docker,非root用户只要加入docker用户组可无需root权限运行docker命令．