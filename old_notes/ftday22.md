问: 是否存在数$0<a<1$和一个无穷正数列$x_1,x_2,...,x_n,...$
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
满足:$1+x_{n+1}\le x_n+\frac an\cdot x_n(n=1,2,...)$总成立? 请说明理由.

利用反证法, 假设真的存在这样一个数列,

把关系式右边写成:

$x_n\cdot(\frac{a+n}n)$

可以推出:

$x_n\ge \frac{n}{n+a}\cdot(1+x_{n+1})$

由于$0<a<1$, 所以$\frac n{n+a}>\frac n{n+1}$

所以有$x_n\gt\frac n{n+1}\cdot(1+x_{n+1})$

接下来又是经典的转换, 当看到$n,n+1$和$x_n,x_{n+1}$我想到把$n$除过去:

$\frac{x_n}{n}\gt\frac{1+x_{n+1}}{n+1}=\frac{x_{n+1}}{n+1}+\frac1{n+1}$

我们构造了一个新数列$\frac{x_n}{n}$,设为$b_n$

那么有:
$$
b_1>\frac12+b_2>\frac13+\frac12+b_3>...>\sum_{i=1}^n\frac1i+b_{n+1}
$$
为方便表示, 我们把$\sum_{i=1}^n\frac1i+b_{n+1}$设为$S_n$

$S_n\to\infty$, $b_1-S_n\to-\infty$, 则一定存在有$b_{m}<0$, 但题目条件里$x_n$是正数列, 所以$b_n$也是正数列, 矛盾.

所以不存在这样的数列和数$a$