# DIN、DIEN 模型
本仓库Fork自[yongqyu/DIEN-tf2](https://github.com/yongqyu/DIEN-tf2)，为其中BASE模型、DIN模型、DIEN模型的核心代码部分加上了注释。
如果想要了解这两个模型的理论知识，可以参考我的两篇博客：
1. [CTR深度学习模型之 DIN(Deep Interest Network) 的理解与例子](https://blog.csdn.net/VariableX/article/details/108796376)
2. [CTR深度学习模型之 DIEN(Deep Interest Evolution Network) 的理解与示例](https://blog.csdn.net/VariableX/article/details/108887709)

或者参考论文原文:
1. [Deep Interest Network for Click-Through Rate Prediction](https://arxiv.org/abs/1706.06978)
2. [Deep Interest Evolution Network for Click-Through Rate Prediction](https://arxiv.org/abs/1809.03672)

## Deep Interest Network for Click-Through Rate Prediction<br/>Deep Interest Evolution Network for Click-Through Rate Prediction

I reference [zhougr1993](https://github.com/zhougr1993/DeepInterestNetwork) and [mouna99](https://github.com/mouna99/dien) code and converte it to TensorFlow 2.0.  
This code performs similarly to the paper on ml-20 and amazon datasets.  
You can modify the ```model``` called in ```main.py``` and then utilize a model such as Base, DIN, DIEN.  

Requirements  
* python 3.6
* tensorflow 2.0

Run ```python main.py```
