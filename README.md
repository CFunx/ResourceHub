# ResourceHub

资源中转站



## WebRTC Windows10 Compiled product 

* 环境准备

  >1. 安装 visual studio 2022
  >
  >2. 安装 windows software Development kit - windows 10.0.22621.3233
  >
  >3. 安装完成Visual studio 之后 必须安装SDK调试工具。打开控制面板->程序与功能，找到刚才安装的最新Windows Software Development Kit，鼠标右键->change。
  >
  >   ![image](/pics/installDbg.jpg)
  >
  >4. 安装 python3.12.x
  >
  >5. 安装 ninja最新版本即可---将其加入到系统环境变量
  >
  >6. 最好将操作系统版本改为英文版本
  >
  >![image](/pics/region.jpg)

* 编译步骤

  >1. 将webrtc.7z.001 解压到对应的目录
  >
  >2. 然后用visual studio2022 打开 src\out\Default\all.sln即可
  >
  >3. 最终工程打开效果如下所示
  >
  >   ![image](/pics/project.jpg)





