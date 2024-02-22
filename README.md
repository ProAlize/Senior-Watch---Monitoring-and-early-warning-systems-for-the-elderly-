# 老人护理助手：基于华为云的室内监测系统
## 1. 项目介绍
该项目为2023年（第十届）全国大学生物联网设计竞赛（华为杯）参赛项目并取得东北赛区二等奖。

## 2. 技术路线
硬件层面项目使用[NVIDIA® Jetson Nano™](https://www.nvidia.cn/autonomous-machines/embedded-systems/jetson-nano/)开发板和红外可见光双模态视觉传感器，算法层面使用[yolov5](https://github.com/ultralytics/yolov5)和[MMPose](https://github.com/open-mmlab/mmpose)实现相应的功能，云平台使用[华为IOT平台](https://www.huaweicloud.com/product/iothub.html)。

![技术路线](/img/技术路线.png)

## 3 设计目标和实现效果

通过双模态视觉传感器实现室内全天对物体和人体姿态的识别，并通过云平台将人体姿态发往手机端。

人体姿态识别效果如下图：  
![](/img/人体姿态识别.gif)  
云平台输出如下：
![](/img/IOT平台.jpg)