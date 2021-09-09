---
layout: wiki
title: 基于单幅图像的三维人体姿态估计
categories: 
description: 实现基于单张图片的人体姿态估计，开启你的CV之旅，体感游戏的未来就靠你了
keywords: 
image: https://i.loli.net/2018/12/24/5c20dc4f1f81e.png
---

# 课题简介
人体姿态估计，就是通过将图片中已检测到的人体关键点正确的联系起来，从而估计人体姿态。人体关键点通常对应人体上有一定自由度的关节，比如颈、肩、肘、腕、腰、膝、踝等。基于单幅图像的2D人体姿态识别，目前发展已经比较成熟，例如CMU的openpose、Facebook的densepose等都已经能够实现准实时的2D人体姿态识别，然而在某些场景下，如体感游戏、3D试衣等，仅提取2D的人体姿态信息是不够的，我们试图基于单幅图像估计得到3D的人体姿态，但由于现有的3D人体姿态数据集往往是实验室内图片，这一任务由于其数据集的缺乏而极具挑战性。

# 人体姿态估计效果
![3.jpg](https://i.loli.net/2018/12/24/5c20e2ff81292.jpg)

![2.jpg](https://i.loli.net/2018/12/24/5c20e2ff7f521.jpg)

![1.png](https://i.loli.net/2018/12/24/5c20e2b9adc84.png)


# 参考论文
[Stacked Hourglass Networks for Human Pose Estimation](https://arxiv.org/pdf/1603.06937.pdf)    

[3D Human Pose Estimation from a Single Image via Distance Matrix Regression](https://arxiv.org/pdf/1611.09010.pdf)    

[Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields](http://openaccess.thecvf.com/content_cvpr_2017/papers/Cao_Realtime_Multi-Person_2D_CVPR_2017_paper.pdf)


# 开源项目
[pose-tensorflow](https://github.com/eldar/pose-tensorflow)    

[openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)     

[pose-hg-3d](https://github.com/xingyizhou/pytorch-pose-hg-3d) 
