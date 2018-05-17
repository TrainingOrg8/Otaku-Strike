# Otaku-Strike
中山大学虚拟游戏实训项目

## 概要
Otaku-Strike是一款基于AR的虚拟现实FPS射击游戏。更多游戏介绍与玩法详看游戏策划。

## 开发工具
利用Unity3D(Version 5.6.5f1 Personal)与太虚AR(VoidAR)sdk (VOIDAR_Unity_v0.1.h_Patch1_Beta)

## 设备要求
中高端安卓机或者ios设备，设备需带有IMU，建议骁龙625同等级性能或以上处理器。

## 版本V1.0
在V1.0版本中，实现了基于SLAM技术的AR敌人生成，能够在现实环境中叠加虚拟物体。同时完成了基本的FPS射击系统的功能，包括:
* 目标瞄准与子弹射出
* 碰撞检测与对象销毁
* 随机敌人生成系统
* 敌人自动寻路系统

在美工方面，由于识别精准度问题，为避免模型与地面贴合效果不佳，选择使用了浮游类怪物模型(含动画效果)。在射击UI里，添加了准星。


[Otaku_Strike V1.0 下载](https://pan.baidu.com/s/1VwWxtDj1C458oJl6jyUfKQ)


## 下一步计划

* 计分系统
* 玩家游戏失败判定机制
* 游戏初始场景等其他场景构建
* 为射击命中增加粒子爆炸特效

## 如何使用VoidAR
[VoidAR SDK下载](https://www.voidar.net/downloads.php)

[SLAM教程](https://jingyan.baidu.com/article/6525d4b17e0254ac7d2e9414.html)

[VoidAR 	AppKey申请](https://cloud.voidar.net/)
