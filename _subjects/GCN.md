---
layout: wiki
title: 链路预测
categories: 
description: 你有没有想过你的下一个微信好友是谁？好奇下一个请求可能来自哪里？通过链路预测来实现吧。
keywords: 
image:https://i.loli.net/2021/09/09/UrasxYwgTRyndMB.png
---

# 课题简介
网络中的链路预测(Link Prediction)是指如何通过已知的网络节点以及网络结构等信息预测网络中尚未产生连边的两个节点之间产生链接的可能性。这种预测既包含了对未知链接（exist yet unknown links）的预测也包含了对未来链接（future links）的预测。

# 社交网络分析
你有没有想过你的下一个微信好友是谁？好奇下一个请求可能来自哪里？


![1.png](https://i.loli.net/2021/09/09/UrasxYwgTRyndMB.png)


Prateek Joshi使用来自全球各地的流行食品店和知名厨师的 Facebook 页面的[数据集](https://networkrepository.com/fb-pages-food.php),做了类似的一个[链路预测](https://www.analyticsvidhya.com/blog/2020/01/link-prediction-how-to-predict-your-future-connections-on-facebook/)，可以作为参考。

# 参考论文


[Link Prediction Based on Graph Neural Networks](https://arxiv.org/pdf/1802.09691.pdf)

[EvolveGCN: Evolving Graph Convolutional Networks for Dynamic Graphs](https://arxiv.org/pdf/1902.10191.pdf)

# 开源项目

[SEAL](https://github.com/muhanzhang/SEAL)

[evolveGCN](https://github.com/IBM/EvolveGCN)
