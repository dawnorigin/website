+++
title = "集群管理"
description = "集群管理模块主要用于对组织下所有集群的管理。"
weight = 7
+++


## 使用 Choerodon 集群管理  
欢迎使用 Choerodon 猪齿鱼集群管理用户手册，如果您是组织管理员，此部分文档将对您有用。本节将对集群管理的作用与使用进行大致的介绍。  

集群管理存在于组织层，统一管理组织下所有的集群；而集群可用于管理组织下各个项目里面的所有环境，即用户可以通过单个集群客户端来管理多个环境，以便于更高效更便捷的统一协调资源。  

## 功能  
* [集群](../cluster-management/cluster)：集群是用于运行k8s的托管群组。有了集群，我们就可以以此来统一调配资源，管理环境。同时，每个集群可以对组织下各个项目设置是否公开，配置后，只有被勾选项目中的环境才能连接到该集群。