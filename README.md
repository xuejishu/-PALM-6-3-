# AI-Studio-项目标题
# 飞桨常规赛：PALM病理性近视预测 6月第3名方案
【常规赛：PALM病理性近视预测】方案
**比赛地址： [https://aistudio.baidu.com/aistudio/competition/detail/85](https://aistudio.baidu.com/aistudio/competition/detail/85)**


[https://github.com/livingbody/Myopia_prediction.git](https://github.com/livingbody/Myopia_prediction.git)



# 一、赛题介绍
## 1. 赛题简介
PALM病理性近视预测常规赛的重点是研究和发展与病理性近视诊断相关的算法。该常规赛的目标是评估和比较在一个常见的视网膜眼底图像数据集上检测病理性近视的自动算法。具体任务是将提供的图像分为病理性近视眼底彩照和非病理性近视眼底彩照，其中，非病理性近视眼底彩照包括正常眼底和高度近视眼底彩照。

 ![](https://ai.bdstatic.com/file/EB6E1DA97ECE4AE79697FD6F6A25F679)

## 2.数据简介
PALM病理性近视预测常规赛由中山大学中山眼科中心提供800张带病理性近视分类标注的眼底彩照供选手训练模型，另提供400张带标注数据供平台进行模型测试。

## 3. 数据说明
本次常规赛提供的病理性近视分类金标准是从临床报告中获取，不仅基于眼底彩照，还结合了OCT、视野检查等结果。

## 4. 训练数据集
文件名称：Train
Train文件夹里有一个fundus_image文件夹和一个Classification.xlsx文件。fundus_image文件夹中数据均为眼底彩照，分辨率为1444×1444，或2124×2056。命名形如N0001.jpg、H0001.jpg、P0001.jpg和V0001.jpg。Classification.xlsx文件中为各眼底图像是否属于病理性近视，属于为1，不属于为0。

## 5.测试数据集
文件名称：PALM-Testing400-Images 文件夹里包含400张眼底彩照，命名形如T0001.jpg。

## 6.提交内容及格式
分类结果应在一个名为“Classification_Results.csv”的CSV文件中提供，第一列对应测试眼底图像的文件名(包括扩展名“.jpg”)，对应title为FileName；第二列包含诊断为PM的患者图像的分类预测概率(值从0.0到1.0)，对应title为PM Risk。示例如下：

![](https://ai.bdstatic.com/file/9B4E52D17D184A0893853C7A3A726BFA)

## 项目结构
```
-|data
-|work
-README.MD
-xxx.ipynb
```
## 使用方式
A：在AI Studio上[运行本项目](https://aistudio.baidu.com/bdcpu2/user/725102/2029451/notebooks/2029451.ipynb)

B：此处由项目作者进行撰写使用方式。
