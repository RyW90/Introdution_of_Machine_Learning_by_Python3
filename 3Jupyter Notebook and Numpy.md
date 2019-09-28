# 3 Jupyter Notebook and Numpy
---

### Jupyter Notebook

```% run```  运行已有的python文件，并导入函数

```%timeit``` 测试单行命令并记录运行时间。由于可能存在中间缓存，所以使用时需要考虑

```%%timeis```运行多行命令并记录时间内

```%time```只运行一次记录时间

### numpy array创建

``` 
import numpy as np    #调用numpy库
```

```nparr = np.array([i for i in range(10)])```

np的array只能一种一种类型，且创建时类型已经确定，不建议使用上述代码



```np.zeros(10)```创建10个0的float64的向量

```np.zeros(shape=(3,5), dtype=int)```创建3行5列全为0的矩阵

```np.ones(3,5)```创建3行5列全为1的矩阵

```np.full((3,5), fill_value=666)```创建3行5列全为666的矩阵

```np.arange(0, 1, 0.2)```创建0起始到1（不含）步长0.2的向量，不填步长默认为1，不填起始默认为0

```np.linespace(0, 20, 10)```创建从0起始到20（含）等分10个点的向量

```np.random.randint(0, 10, 10)```从0到10（不含）取10个随机整数

```np.random.randint(0, 10, size=(3,5))``` 3行5列的矩阵，包含从0到10（不含）的随机整数

```np.random.seed``` 显式的指定种子（生成指定的随机数）

```np.random.random(size=(3,5)）```3行5列的矩阵，包含从0到1（不含）的随机浮点数

```np.random.normal(0, 1, size=(3,5)）```3行5列的矩阵，包含均值0方差1随机浮点数

```np.random.normal?```或```help(np.random.normal)```或```Shift+Tab```查看帮助文档


**To be continued...**