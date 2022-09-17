# 非零中心(No Zero Centered)的理解

设神经元的激活函数为s(x)，以sigmoid函数为例，则
$$
s(x) = \frac{e^{-x}}{1+e^{-x}}
$$
梯度下降的目的是让损失函数最小，因此进行梯度下降时，神经元参数ω如下式，L为损失函数，α为学习率或者步长：
$$
\omega_i = w_i - \alpha\frac{\partial L}{\partial \omega_i}
$$

下面以单个神经元举例：

![](D:\typora\note\Notebook\RL\media\neure.png)
$$
z=x_1\omega_1 + x_2\omega_2 + x_3\omega_3 +b  \\

输出\quad out = s(z) = \frac{e^{-z}}{1+e^{-z}}
$$
设损失函数L为:
$$
L(x) = (y' - y)^2
$$
