# 4 KNN算法
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
### 基本概念
K-Nearest Nrighbors K近邻算法 KNN
找出最近的K个点，并对测试数据集进行分类

超参数hyperparameter：在算法运行前就需要决定的参数

模型参数parameters： 在算法过程中学习到的参数

KNN算法没有模型参数

KNN算法中K是超参数

曼哈顿距离

$$\sum \left| {x_i^\left(a\right) - x_i^\left(n\right) }\right|$$

明可夫斯基距离

$$\left(\sum\left(x_i^\left(a\right) - x_i^\left(n\right)^p\right)^\frac{1}{p}$$