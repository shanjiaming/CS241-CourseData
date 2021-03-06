### week01：高精度四则运算的实现

高精度四则运算：对于加法、减法对位相加或相减；对于乘法利用朴素的 $O(n^2)$ 模拟实现；对于除法模拟移位、试除操作。

特别提及：对于大整数乘法，有着一种时间复杂度可以达到 $O(n \log n)$ 的算法：Fast Fourier Transformation（快速傅里叶变换），以及与之思想相同的基于模意义下原根的 NTT（快速数论变换），这里不赘述，有兴趣的同学可以自行上网查询相关资料。

本周作业的代码参见 Weekly-homework 文件夹下的 week01 子文件夹的 main.cpp ，内部的 Number 类重载了高精度的加减乘除，Expression 类在实现四则运算的基础上，进一步实现了表达式求值。

本周题目主要难点：**高精度除法★★**