## 这是一个对于神经网路的学习项目

#### fully connected neural network

实现了手写数字识别的全连接神经网络

结构看起来有点复杂，几乎是纯手写的，只是使用了numpy进行矩阵运算

#### Automatic differentiation

使用了链式法则实现了自动求导的功能。

##### 注意事项：
自动求导中的向量都已经统一修改成为矩阵的形式，即 $\overrightarrow{v}_n \overrightarrow{} V_{n \times 1 }$， 但是需要添加少量的判断条件来处理向量点乘的情况

可能会存在遗漏的情况，但是目前程序还是跑起来了
