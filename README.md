# 
使用神经网络对火星Gale沙粒、土壤图像进行像素级分割
1、配置
Python3.8
Pytorch2.2.2
Model: CNN
损失函数：均方误差（MSELOSS）
batch_size：8
epochs：350
优化器：NAdam
# 
2、数据集
收集来自Gale撞击坑，由好奇号火星车拍摄的沙粒、土壤照片
利用ps对每一张照片进行像素级分割，背景为黑色，沙粒对象为白色
计算每一张标签的权重来增强训练效果
共60个样本



