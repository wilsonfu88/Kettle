通过Kettle做一个数据库数据交换的示例


转换定义
![转换定义](https://github.com/wilsonfu88/Kettle/blob/master/%E8%BD%AC%E6%8D%A2%E5%AE%9A%E4%B9%89.png)


作业配置
![作业配置](https://github.com/wilsonfu88/Kettle/blob/master/%E4%BD%9C%E4%B8%9A%E9%85%8D%E7%BD%AE.png)


Kettle使用中的一些小技巧
1、MySQL中文乱码
数据库编码配置
数据库连接中设置，MySQL连接高级里面设置连接成功后执行set names utf8mb4;选项里面加上characterEncoding=utf8参数

2、