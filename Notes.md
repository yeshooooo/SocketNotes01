[tcp/ip socket 高级编程](https://www.bilibili.com/video/BV12E41197zn/?spm_id_from=333.788.recommend_more_video.2&vd_source=c6ca89f75d00cd4da634736edfcca1ae)

个人笔记

# 1. TCP/IP基础

### ISO/OSI七层参考模型

每个对等层传输单位统称为PDU(protocal data unit)

* 应用层

​	提供应用程序间通信

​	==传输单位apdu==

​	application pdu

* 表示层

​	处理数据格式、数据加密等

​	==传输单位ppdu==

​	presentation pdu

* 会话层

​	建立、维护和管理会话

​	==传输单位spdu==

​	session pdu

* 传输层

​	建立端到端连接

​	==传输单位segment==

* 网络层

​	寻址和路由选择

​	==传输单位package，分组==

* 数据链路层

​	介质访问、链路管理

​	==传输单位frame，帧==

* 物理层

​	比特流传输

​	==传输单位比特==





# 2. socket编程





# 3. 进程间通信





# 4. 线程篇



# 5. 实战:miniftpd