## Windows Server学习笔记



### 01 课程环境准备

- 一个下载微软工具的网站：msdn.itellyou.cn（MSDN我告诉你）
  - **这是下载微软工具最全的网站**

<img src="C:\Users\Duuuzx\AppData\Roaming\Typora\typora-user-images\image-20250921163325198.png" alt="image-20250921163325198" style="zoom: 67%;" />

- Windows server 2016 迅雷下载链接：ed2k://|file|cn_windows_storage_server_2016_x64_dvd_9327778.iso|4808439808|4E70FB4EFEF1F0D93C8600BE6CF62D82|/
- 下载完成后直接在VMware上安装系统

------

### 02 管理账号和文件共享

#### 1、WorkGroup 和 Domain

> 工作组和域，其中微软推荐域场的工作管理模式

------

一些想法

1、使用远程桌面服务RDS，连接后用GPU训练模型

2、Hyper -v来实现虚拟化，创建多个虚拟机，每个虚拟机分配特定的硬件资源（通过**基于功能的安装**来启用Hyper-V）

3、看一看这个方法能不能提供可用的思路：[新手教程！远程连接服务器，用GPU算力跑深度学习项目！ -人工智能/机器学习/深度学习_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1xDCbYCEZo/?spm_id_from=333.337.search-card.all.click)