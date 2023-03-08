# 化学96孔板项目

> sicau 96孔板实验项目，用于实现荧光物质判断自动化

## 项目介绍

96孔板是一种常用的高通量试剂盘，是化学和生物学等科研领域中常用的实验仪器之一，主要用于处理大量的反应、筛选和分析。

![96borad](./static/96borad.jpg)

在许多化学实验中，研究人员需要检测反应产物的颜色变化来判断反应是否成功。然而，目前的检测方法主要依靠人工观察，存在误差率高、效率低等问题，且随着反应规模的增大，观察难度也相应增加。因此本研究的立题依据是针对96孔板实验中的一个常见问题，即如何快速准确地识别96孔板中是否有孔洞相对标准发生改变。

本项目开发一种自动化的检测方法，能够准确快速地识别和基准样本颜色出现差异的部分，帮助科研人员进行快速的高通量筛查。

## 完成内容

主要提供API接口模式，现在已经完成
- [x] 读取图片,并使用YOLO定位进行裁剪96孔板
- [x] 使用孔的位置信息提取孔的荧光信息
- [x] 以最左侧作为标准列，快速检测并定位出现变色的孔的位置

