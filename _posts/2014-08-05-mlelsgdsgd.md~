---
layout: post
title: "MLE,LS,GD,SGD"
description: ""
category: Machine Learning
tags: [Logistic Regression, SGD]
---
{% include JB/setup %}





###MLE 与 Least Square

一个是最大似然估计，一个是最小二乘法，都是优化的思路。在regression问题上，如果使用MLE，

且让![](http://latex.codecogs.com/gif.latex?P%28Y%7CX%29%20%3D%20Gauss%28F%28X%29%2C%5Cepsilon%29)
，

则![](http://latex.codecogs.com/gif.latex?P%28Y%7CX%29%20%5Cpropto%20exp%28%28Y-F%28X%29%29%5E2%29).

将所有的MLE相乘可以得到与LS一样的结果。

即假设每一点都服从一个均值为F(X)的正态分布，寻找这样的F(X)使得 P(Y|X)最大。

###GD 与 SGD 

对于一个cost function：(test)
![](http://latex.codecogs.com/gif.latex?J%28%5Ctheta%29%20%3D%20%5Csum%20J%28%5Ctheta_i%29)

i为第i个instance，GD就是更新的时候这么做：
![](http://latex.codecogs.com/gif.latex?%5Ctheta%20%3D%20%5Ctheta%20&plus;%20%5Calpha%20*%20%5Cfrac%7B%5Cpartial%20J%28%5Ctheta%29%7D%7B%5Cpartial%20%5Ctheta%7D)

SGD这么做：
![](http://latex.codecogs.com/gif.latex?%5Ctheta%20%3D%20%5Ctheta%20&plus;%20%5Calpha%20*%20%5Cfrac%7B%5Cpartial%20J%28%5Ctheta_i%29%7D%7B%5Cpartial%20%5Ctheta%7D)

GD每一次迭代要对所有instance都求导，会慢一些。
