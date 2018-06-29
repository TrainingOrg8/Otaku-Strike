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
## 版本V2.0
相较于V1.0，更新内容如下：
* 模型资源美化，
* 字体优化，改善字体模糊，提高字体美观性
* 添加HP条，与敌人接触将扣血，将至0以下将死亡
* 添加了道具系统，暂提供2种道具：Freeze_All & clear_All
* 提升敌人多样化，暂提供2种敌人模型，随机生成
* 调整命中率，添加子弹特效，子弹轨迹更明显
* 添加敌人命中爆炸特效
* 添加结算页面
## 版本V3.0
相较于V2.0，更新内容如下：
* 提供2种模式，并添加模式选择页面，原版本定位为normal模式，即倒计时模式，添加speed模式，即在最少时间内击杀足够敌人
* 改进结算规则，分数将与击杀怪数目、时间、HP值挂钩
* 区分游戏结束类型，因HP扣减至0视为游戏结束，提示Label为 "Game Over",在两者模式中分别达成倒计时完毕或者击杀足够敌人提示Label为"Congratulations"

在美工方面，由于识别精准度问题，为避免模型与地面贴合效果不佳，选择使用了浮游类怪物模型(含动画效果)。在射击UI里，添加了准星。


### Unitypackage下载
[Otaku_Strike V1.0 UnityPackage资源包 下载](https://pan.baidu.com/s/1PuSSEEZ8qDYLFB7vlMQs-A)

[Otaku_Strike V3.0 UnityPackage资源包 下载](https://pan.baidu.com/s/1fRpqLYXiFXZg6ZH-M7iw7w)


### 安卓打包
因开发环境原因，暂只提供安卓版本，需要ios版本的可下载Unitypackage结合VoidAR教程自己打包

[Otaku_Strike V1.0 安卓端AKP下载](https://pan.baidu.com/s/1VwWxtDj1C458oJl6jyUfKQ)

[Otaku_Strike V3.0 安卓端AKP下载](https://github.com/TrainingOrg8/Otaku-Strike/blob/master/Otaku_StrikeV3.0.apk)

iOS版需用Mac OS系统打包，自己下载Unity资源包自己打包。



## 如何使用VoidAR
[VoidAR SDK下载](https://www.voidar.net/downloads.php)

[SLAM教程](https://jingyan.baidu.com/article/6525d4b17e0254ac7d2e9414.html)

[VoidAR 	AppKey申请](https://cloud.voidar.net/)
