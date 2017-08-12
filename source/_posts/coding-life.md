---
title: Coding Life
date: 2017-08-12 14:31:23
tags: Learning Memo
---

# Docker Study

[Docker][lnk_Docker]

### Docker 简介

```
Docker是一个开源的引擎，
可以轻松的为任何应用创建一个轻量级的、可移植的、自给自足的容器。
开发者在笔记本上编译测试通过的容器可以批量地在生产环境中部署，
包括VMs（虚拟机）、bare metal、OpenStack 集群和其他的基础应用平台
```

<!--more-->

### Docker 应用实例-探索篇

[Docker App][lnk_DockerApp]

```
dockers4ibcp

使用说明 | instructions
build_dockerfile4all.sh 使用dockerfile4all创建容器镜像，且拷贝ibcp.app.xml，ibcp.service_routing.xml到容器的ibcp配置目录。
deploy_ibcp_all.sh 下载并部署ibcp全部模块。
initialize_datastructures.sh 初始化数据结构。
使用时注意提前修改配置文件内容。
测试环境时，配置文件中涉及的主机，建议修改本机host文件指向。
脚本中使用了额外文件作为初始化顺序说明。

启动 | running
docker run –name ibcp-srv-db -p 3306:3306 -d -e MYSQL_ROOT_PASSWORD=1q2w3e mysql:5.7 启动MYSQL容器
docker run –name=ibcp-srv-app-01 –link=ibcp-srv-db -p 8080:8080 -d ibcp-all:1476945979 启动ibcp容器
docker exec -it ibcp-srv-app-01 ./ibcp_tools/initialize_datastructures.sh 执行ibcp容器中数据结构

修改访问主机host：192.168.3.60 ibcp-srv-app
```

***Author:***
+ [NiurenZhu][lnk_NiurenZhu]
+ [XiaoCangcang][lnk_XiaoCangcang]

[lnk_Docker]: https://hub.docker.com/ "Docker"
[lnk_DockerApp]: https://github.com/cyitianyou/dockers4ibcp "Docker App"
[lnk_NiurenZhu]: https://github.com/NiurenZhu "NiurenZhu"
[lnk_XiaoCangcang]: https://github.com/cyitianyou "XiaoCangcang"
