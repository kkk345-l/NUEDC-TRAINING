# 备赛规划
## 1.小组信息及分工
成员一（主做视觉，副做软件）  
成员二（软件）  
成员三（硬件）  
## 2.方向选择
___控制类___  
__备选题__：21年送药小车 23年激光追踪  
## 3.题目分析
### 送药小车
主要技术：电机控制，巡线，视觉识别，各种通信（串口，蓝牙）
#### 视觉处理
使用k210对病房数字进行识别(神经网络）  
openmv进行巡线（也可使用其他巡线方式）
#### 电机控制
电机：520电机  
电机驱动：tb6612  
亚克力车架  
#### 其他
锂电池若干  
主控：stn32c8t6  
蓝牙模块：HC06,jdy31  
红外传感器（识别药品）
## 4.学习计划
+ __3.17~3.23:__<br/> 搭建小车的基本框架<br/>学习k210 openmv的视觉知识
+ __3.24~3.30:__<br/> 调参，小车实现基本运动功能
+ __3.31~4.6：__<br/> 基本完成题目基础部分
+ __4.7~4.13：__<br/> 搭建双车<br/> 学习蓝牙通信，保证两车通信
+ __4.14~4.20:__<br/> 完成题目发挥部分
## 技术栈
成员一

  

