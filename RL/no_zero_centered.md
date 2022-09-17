# 非零中心(No Zero Centered)的理解

设神经元的激活函数为s(x)，以sigmoid函数为例，则
$$
s(x) = \frac{e^{-x}}{1+e^{-x}}
$$
梯度下降时，神经元参数ω如下式进行迭代为，L为损失函数，α为学习率或者步长：
$$
\omega_i = w_i - \alpha\frac{\partial L}{\partial \omega_i}
$$

下面以单层神经网络举例：

