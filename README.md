# blance_Bike

![](2.Structure/xuan.jpg)

> 项目视频：[【自制】我把自行车做成了 自 动 驾 驶 ！！【硬核】](https://www.bilibili.com/video/BV1fV411x72a)

## 文件说明

`Hardware`里面是控制器的PCB文件，基于ESP32，搭载MPU6050，通过CAN总线连接驱动器。

`Structure`里面是车身结构设计文件，step是Fusion导出的可能有些BUG，建议直接下载这个Fusion360的工程在软件里打开：https://a360.co/2TOtZRd

软件部分由于涉及到FOC驱动器的耦合并不是通用的所以暂时未放出。



