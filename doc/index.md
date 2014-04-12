一、硬件规划
=============

1.1 硬件配置
------------

物理机配置：

- CPU： 2 x 6核 (HT) Xeon E5-2620
- 内存： 128 GB
- 存储： 10TB (RAID 5)

虚拟机：

- CPU： 双核
- 内存： 8 GB
- 存储： 1 TB



1.2 拓扑结构
------------

- NameNode: 2台
- ResourceManager: 1台
- DataNode + NodeManager: 17 台


二、系统安装配置
==============

2.1 系统
--------

采用 Ubuntu Server 12.04 LTS。

2.2 Hadoop 安装
----------------

选择 CDH 5.0。

三、Hadoop
===========

3.1 Hadoop 安装
----------------

3.2 Hadoop 配置
----------------

### 3.2.1 core-site.xml
### 3.2.2 hdfs-site.xml
### 3.2.3 mapred-site.xml

3.3 Hadoop 启动
------------------


