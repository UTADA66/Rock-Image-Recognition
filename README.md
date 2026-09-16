# Rock-Image-Recognition
基于飞桨18岩石图像分类识别
# 岩石图像识别
基于飞桨PaddlePaddle ResNet18实现岩石图像分类，识别花岗岩、砂岩、石灰岩。

## 项目环境
Python3.10 + PaddlePaddle
开发平台：百度AI Studio

## 文件说明
- main.ipynb：完整训练+图片预测代码
- rock_infer_model.json：推理模型结构文件
- rock_infer_model.pdiparams：推理模型权重文件

## 使用方法
1. 运行main.ipynb，完成数据集加载、模型训练
2. 调用predict函数，输入岩石图片，自动识别岩石类别

## 项目简介
本项目使用迁移学习训练深度学习图像分类模型，实现野外岩石简易识别，属于科创实践项目。
