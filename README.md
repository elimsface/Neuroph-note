# Neuroph-note
一些关于神经网络的理解

神经网络其实是一个很简单的东西，感知机是最简单的神经网络（双层网络：输入层和输出层，没有隐含层）
多层神经网络比感知机多了一个隐含层（隐含层可以有多层，自己设置）。权值和偏移量（偏值）都是由计算机来随机取得，并根据每次迭代自动修改。认为需要设置的是精度、步长、转移函数 f(s) 类型。

人工神经网络不仅可以做分类问题，还可以做回归问题（预测问题居多）。对于机器来说，并不了解数据下的真正含义，他们看得是大量数据背后数据本身的规律。回归问题和分类问题对局计算机来说是一类问题（数据问题）。

难点在于源码中计算机是如何学习的？也就是learn（）函数！！！
