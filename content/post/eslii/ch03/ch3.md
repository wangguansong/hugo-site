# 线性回归模型

## 简述

线性回归模型假设回归方程 E(Y|X) 与其输入变量 X_1，……，X_p 为线性关系。线性模型在计算机时代之前的统计学中已经基本成熟，但即使在今天的计算机时代，它仍然值得研究和应用。线性模型足够简洁，而且经常可以对输入变量如何影响输出变量有充足的而且可解释的说明。在实际预测中，特别是在训练样本不够大、数据中信噪比低或稀疏数据集的情况下，线性模型有时会优于复杂的非线性模型。此外，线性模型可以应用到对输入变量的（非线性）转化后的变量上，从而拓展了模型对现实的模拟能力。这种推广也被称为基函数方法，会在第五章讨论。

本章节我们讨论线性回归模型，下一章我们讨论线性分类模型。针对一些问题我们会相对深入，因为我们认为理解线性模型是进一步理解非线性模型的关键。实际上，很多非线性方法都是本章讨论的线性方法的直接推广。

## 线性回归模型和最小二乘

如同第二章，我们有一个输入参数向量*X*，我们要预测一个数字类型的输出变量*Y*。线性回归模型可写为：

等式(3.1)

线性模型假设真实的回归方程 E(Y|X) 是线性的，或者假设线性模型是对真实的合理的近似。其中 *beta_j* 为未知参数

# Keywords

- regression
