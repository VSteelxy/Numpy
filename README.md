# Numpy快速上手
### 简单介绍
NumPy(Numerical Python) 是 Python 语言的一个扩展程序库，支持大量的维度数组与矩阵运算，此外也针对数组运算提供大量的数学函数库。

NumPy 的前身 Numeric 最早是由 Jim Hugunin 与其它协作者共同开发，2005 年，Travis Oliphant 在 Numeric 中结合了另一个同性质的程序库 Numarray 的特色，并加入了其它扩展而开发了 NumPy。NumPy 为开放源代码并且由许多协作者共同维护开发。

NumPy 通常与 `SciPy`（Scientific Python）和 `Matplotlib`（绘图库）一起使用， 这种组合广泛用于替代 MatLab，是一个强大的科学计算环境，有助于我们通过 Python 学习数据科学或者机器学习
***

Author | VSteelxy  
 :-: | :-:    
Email | cqu32edu64lh78@qq.com  

***
- 相关链接  
    - [Numpy 官网] http://www.numpy.org/
    - [SciPy 官网] https://www.scipy.org/
    - [Matplotlib 官网] https://matplotlib.org/  
 
上面都是一些比较官方的叙述，下面的内容都是作者根据自己的理解拼凑起来的，你没有听错，是我拼凑起来的；主要是自己接触的东西比较散，没有统一化，时间一长的话，基本上就又是新的知识了，所以想把一些自己的想法写下了，也可以留作纪念；第一次写博客，有冒犯的地方希望大家能够原谅，有不同的想法的欢迎大家戳我哦

:blush:  :smile:
### 目录  
- [Numpy 数据结构(内存结构)](https://github.com/VSteelxy/Numpy/wiki/Numpy%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)  
```Numpy 最重要的一个特点是其 N 维数组对象 ``` `ndarray,`提起数组我们也许是高兴中还夹杂着难过，高兴的是数组我们或多或少都有所接触，难过的是数组里面的指针一顿操作猛如虎(把我们唬得云里雾里),我想这里大家不用在意指针;Numpy是python的一个扩展程序，操作和python里面的`列表`差不多，只是比`列表`表更加强大;了解它的内存结构方便我们后续的创造和操作它  
