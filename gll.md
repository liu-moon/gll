# 随机变量

## 离散型随机变量

如果随机变量 X 所有可能的取值是有限或可列多个，则称为离散型随机变量，
则其分布可表示为

| X | $x_{1}$ | $x_{2}$ | …… | $x_{n}$ | …… |
| :--: | :--: | :--: | :--: | :--: | :--: |
|P| $p_{1}$ |$p_{2}$| …… | $p_{n}$ | …… |

或

$\begin{pmatrix} x_{1}&x_{2} &… & x_{n} &… \\ p_{1}&p_{2} &… & p_{n} &…\end{pmatrix}$

这种表示称为分布列。

其中 $$p_{i}=P(X=x_{i}) \geq 0 (i=1,2,…n,…)，\sum_{1}^{ \infty } p_{i}=1,F(x) = \sum_{x_{i} \leq x}p_{i}$$

## 连续型随机变量

设随机变量X的分布函数为$F(x)$, 如果存在非负可积函数，$f(x)$ $x\in R$,使得 $\forall x\in R $,有$F(x)= \int_{-\infty}^{x}f(t)dt$,则称X为连续型随机变量，$f(x)$称为X的概率密度函数，简称密度函数

概率密度函数一定满足：$\int_{-\infty}^{+\infty}f(x)dx=1$

连续型随机变量的分布函数一定是R上的连续函数，但分布函数在R上连续的随机变量不一定都是连续型的（Cantor分布）

## 均匀分布

在a,b区间上等可能取值的随机变量称为a,b区间上的均匀分布。均匀分布在a,b区间上的等可能性决定它的密度函数在a,b区间上必为常数

$f(x)=\begin{cases} \frac{1}{b-a} \,\,\,\,\, x \in \left [ a,b \right ], \\  0 \,\,\,\,\,  其他 \end{cases}$

## 柯西分布

$f(x)= \frac{1}{\pi} \frac{1}{1+x^2},\,\,\,\,\,	-\infty<x<+\infty$



<div align=left><img src="/picture/3_2_4.jpg" width="800px">


## 伯努利试验

<div align=left><img src="/picture/伯努利.jpg" width="800px">
## 二项分布

<div align=left><img src="/picture/二项1.jpg" width="800px">
<div align=left><img src="/picture/二项2.jpg" width="800px">
<div align=left><img src="/picture/二项习题1.jpg" width="800px">
<div align=left><img src="/picture/二项习题2.jpg" width="800px">



## 泊松分布

设随机变量X所有可能的值为0，1，2，…，而取各个值的概率为

$P\left \{ X=k \right \}=\frac{\lambda^k e^{-\lambda }}{k!}$,	k=0,1,2,…,

其中$\lambda>0$是常数，则称X服从参数为$\lambda$的泊松分布，记为X~$\pi(\lambda)$.

易知，$P\left \{ X=k \right \}\geq0$,	k=0,1,2,…,且有

$\sum_{k=0}^{\infty} P\left \{ X=k \right \}=\sum_{k=0}^{\infty} \frac{\lambda^k e^{-\lambda }}{k!} =e^{-\lambda } \cdot \sum_{k=0}^{\infty}\frac{\lambda^k}{k!}=e^{-\lambda}\cdot e^\lambda=1$



<div align=left><img src="/picture/泊松1.jpg" width="800px">

例题

<div align=left><img src="/picture/泊松例1.jpg" width="800px">
<div align=left><img src="/picture/泊松例2.jpg" width="800px">


## 几何分布

<div align=left><img src="/picture/几何分布.jpg" width="800px">

例题

<div align=left><img src="/picture/几何分布例1.jpg" width="800px">
<div align=left><img src="/picture/几何分布例2.jpg" width="800px">
<div align=left><img src="/picture/几何分布例3.jpg" width="800px">


## 指数分布


<div align=left><img src="/picture/指数分布.jpg" width="800px">
<div align=left><img src="/picture/指数分布1.jpg" width="800px">


## 正态分布

<div align=left><img src="/picture/正态分布.jpg" width="800px">
<div align=left><img src="/picture/正态分布1.jpg" width="800px">
<div align=left><img src="/picture/正态分布2.jpg" width="800px">

例题   

<div align=left><img src="/picture/正态分布3.jpg" width="800px">
<div align=left><img src="/picture/正态分布4.jpg" width="800px">



## 随机变量函数的分布

离散型

<div align=left><img src="/picture/离散型.jpg" width="800px">

连续型

<div align=left><img src="/picture/连续型.jpg" width="800px">

例题

<div align=left><img src="/picture/连续型1.jpg" width="800px">
<div align=left><img src="/picture/连续型2.jpg" width="800px">
<div align=left><img src="/picture/连续型3.jpg" width="800px">


## 期望

定义：

<div align=left><img src="/picture/期望.jpg" width="800px">
<div align=left><img src="/picture/期望1.jpg" width="800px">

例题：

<div align=left><img src="/picture/期望例1.jpg" width="800px">

离散连续：

<div align=left><img src="/picture/期望例2.jpg" width="800px">

例：

<div align=left><img src="/picture/期望例3.jpg" width="800px">

性质：

<div align=left><img src="/picture/期望性质.jpg" width="800px">
<div align=left><img src="/picture/期望性质1.jpg" width="800px">

例题：

<div align=left><img src="/picture/期望习题.jpg" width="800px">
<div align=left><img src="/picture/期望习题1.jpg" width="800px">


## 方差
<div align=left><img src="/picture/方差.jpg" width="800px">
<div align=left><img src="/picture/方差1.jpg" width="800px">

例题

<div align=left><img src="/picture/方差例.jpg" width="800px">
<div align=left><img src="/picture/方差例1.jpg" width="800px">


## 原点矩与中心距
<div align=left><img src="/picture/原点矩.jpg" width="800px">


例题

<div align=left><img src="/picture/原点矩例.jpg" width="800px">
<div align=left><img src="/picture/原点矩例1.jpg" width="800px">


## 期望和方差的补充性质

<div align=left><img src="/picture/补充.jpg" width="800px">

例题

<div align=left><img src="/picture/补充例1.jpg" width="800px">
<div align=left><img src="/picture/补充例2.jpg" width="800px">
<div align=left><img src="/picture/切比雪夫.jpg" width="800px">
<div align=left><img src="/picture/切比雪夫1.jpg" width="800px">

例题

<div align=left><img src="/picture/切比雪夫例.jpg" width="800px">
<div align=left><img src="/picture/切比雪夫例1.jpg" width="800px">
<div align=left><img src="/picture/切比雪夫例2.jpg" width="800px">
<div align=left><img src="/picture/不存在.jpg" width="800px">
<div align=left><img src="/picture/不存在1.jpg" width="800px">


例题

<div align=left><img src="/picture/不存在例.jpg" width="800px">
<div align=left><img src="/picture/不存在例1.jpg" width="800px">

