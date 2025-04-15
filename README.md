# Maching-Learning-记录学习进展

## 个人背景

**数学**：高中河南文科高考数学149，后来考研数三137，微积分概统线代基础尚可

**专业**：本硕经济类，大四一门专业课中完整了解过各类主流机器学习算法，实操过一门大作业

**编程**：Python了解基础知识，Numpy,Pandas,Matplotlib了解基本功能

## 3.11-3-21 完成有监督学习部分 

[吴恩达机器学习系列课程———有监督的机器学习：回归与分类，网课链接](https://www.coursera.org/learn/machine-learning)

**线性回归**：代价函数、梯度函数、梯度下降

**分类**：sigmoid函数、交叉信息熵构造代价函数，梯度函数和梯度下降同线性回归

**学习率**：过高则代价函数值无法收敛，过低又导致收敛较慢

**标准化**：主要用Z-score，将各个特征的范围统一，减少极端值影响

**特征工程**：增加高次项、交叉项等，但可能导致过拟合（高方差）

**正则化**：对代价函数添加正则项，惩罚特征系数向量，避免过拟合问题

**应用**：可直接调用scikit-learn库，但完整了解算法实现过程非常有益！
