# 【飞桨学习赛：手机行为识别】第6名方案
## 项目描述
此手机行为预测属于分类任务，本次实验使用xgboost模型，XGBoost的全称是eXtreme Gradient Boosting，它是经过优化的分布式梯度提升库。XGBoost是大规模并行boosting tree的工具，作为集成学习的典型代表，它具有可移植性，速度快等明显优势。

## 项目流程图
![image](https://github.com/oxygen1010/paddlepaddle/blob/main/%E6%B5%81%E7%A8%8B%E5%9B%BE.png)

## 未来展望
进一步的打算是可以根据特征重要性挑选出比较重要的特征，将依照这些特征进行数据清洗，并且剔除一些不太重要的特征。相对于baseline，做的调整是使用了较为强大的集成学习算法xgboost，效果较好。
