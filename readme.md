# 基于多层感知机的手写数字识别算法及实现
![image](https://github.com/cgpeter96/assignment/blob/master/data/mnist_100_digits.png)
## 实验介绍
本次实验需要使用python(3.0以上)实现基于多层感知机的手写数字识别算法.请将全部代码
写在Network.py中。请独立完成本次实验。

## 实验数据
本实验数据来自MNIST数据集，可以通过mnist_loader.py将数据载入到程序中


### 数据概览
本数据划分为训练集，验证集，测试集（training_data, validation_data, test_data）
数据大小分别为（50000,784）,(10000,784),(10000,784)
每个数据集的具体形式是
```python
[(image,label1)....(imageN,labelN)]
```

## 实验内容
本实验你需要补全Network.py中代码(当然你可以自己新建一个，但要求突出反向传播部分)。

1. 请在文件抬头用注释写明学号与姓名
```python
'''
name:小米
id:111
'''
#your code
```
2. 完成多层感知机代码，实现mnist分类
3. 画出loss,accuracy曲线

## 注意事项
- 本实验目的是加深学生对神经网络以及反向传播的理解，并且熟悉python编程。本次实验
禁止使用深度学习库。
- 希望你可以合理利用注释增加代码的可读性
- 本着诚实守信的原则，本实验对代码进行严格查重，对于作弊的同学，全部不合格

## 作业提交
- 本次实验开始于    ，请在   之前提交
- 请将整个文件打包成zip格式，其中包括相关实验截图，发送至邮箱peter_chen_jaon@foxmail.com
- 命名格式 姓名_学号_ass.zip


## 如有错误请联系发邮件peter_chen_jaon@foxmail.com
