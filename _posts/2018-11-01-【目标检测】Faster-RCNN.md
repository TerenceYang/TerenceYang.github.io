---
layout:     post
title:      【目标检测】Faster-RCNN
subtitle:   Faster RCNN算法详解
date:       2018-11-01
author:     Terence
header-img: img/post-bg-re-vs-ng2.jpg
catalog: true
tags:
    - Faster-RCNN
---

> Faster RCNN是继RCNN，fast RCNN之后，目标检测界的领军人物Ross Girshick团队在2015年的又一力作。简单网络目标检测速度达到17fps，在PASCAL VOC上准确率为59.9%；复杂网络达到5fps，准确率78.8%。
>

# 思想
从RCNN到fast RCNN，再到本文的faster RCNN，目标检测的四个基本步骤（候选区域生成，特征提取，分类，位置精修）终于被统一到一个深度网络框架之内。所有计算没有重复，完全在GPU中完成，大大提高了运行速度。

# 候选区域生成网络Region Proposal Networks（RPN）

### RPN网络结构解析




我在博客中的每篇文章都是我一字一句敲出来的，转载的文章我也注明了出处，表示对原作者的尊重。同时也希望大家都能尊重我的付出。

谢谢~