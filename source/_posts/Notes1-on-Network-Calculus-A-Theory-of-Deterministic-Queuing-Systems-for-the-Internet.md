---
title: >-
  Notes1 on Network Calculus: A Theory of Deterministic Queuing Systems for the
  Internet
date: 2022-06-14 20:30:52
tags:
mathjax: true
---
大家好！我是韩洋！欢迎进入我的个人主页！开工了，加油！奋斗出一个好的未来！'$\pi$'
$\frac{dR}{dt}=r(t)$

$$
A = \begin{bmatrix}
        a_{11}    & a_{12}    & ...    & a_{1n}\\
        a_{21}    & a_{22}    & ...    & a_{2n}\\
        a_{31}    & a_{22}    & ...    & a_{3n}\\
        \vdots    & \vdots    & \ddots & \vdots\\
        a_{n1}    & a_{n2}    & ... & a_{nn}\\
    \end{bmatrix} , b = \begin{bmatrix}
        b_{1}  \\
        b_{2}  \\
        b_{3}  \\
        \vdots \\
        b_{n}  \\
    \end{bmatrix}
$$

$$
P(A_i \mid B) = \frac{P(B\mid A)P(A_i)}{\sum_{j=1}^{n}P(A_j)P(B \mid A_j)}
$$

\begin{equation}
  sign(x)=\begin{cases}
        -1 & \text{if $x<0$},\\
        0 & \text{if $x=0$},\\
        1 & \text{if $x>0$}.
       \end{cases}
\end{equation}

$$
  \begin{split}
  \frac{\partial{\mathcal{E}}}{\partial{x_l}} & = 
  \frac{\partial{\mathcal{E}}}{\partial{x_L}}\frac{\partial{x_L}}{\partial{x_l}}\\\\
  & = \frac{\partial{\mathcal{E}}}{\partial{x_L}}\Big(1+\frac{\partial{}}{\partial{x_l}}\sum_{i=l}^{L-1}   
  \mathcal{F}(x_i,\mathcal{W}_i)\Big)
  \end{split}
$$