# 使用一种有序的方式，对多个Socket进行统一管理和调度
  * 参考示例图
  ![](./Res/Select机制/0_1298022379T3Wh.gif)
  * 通过调用Select()函数来监控一系列的文件句柄，一旦其中一个文件句柄发生了IO动作，该Select()调用就会返回
  * windows和linux套接字中的select机制浅析：http://www.cnblogs.com/lidabo/p/3804411.html
