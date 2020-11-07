## 对数篇(2) 换底公式
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
上期答案:

(1):

a<sup>log<sub>a</sub>b</sup>=b

=> log<sub>b</sub> a<sup>log<sub>a</sub> b</sup> =1

=>log<sub>a</sub>b·log<sub>b</sub>a=1

(2):

$2\lg\frac{x-y}{2}=\lg x+\lg y$

=>$\lg\frac{(x-y)^2}{4}=\lg xy$

=>$(x-y)^2=4xy$

=>$(\frac{x}{y})^2+6(\frac{x}{y})+1=0$

=>$\frac{x}{y}=3-2\sqrt2$(舍), $\frac{x}{y}=3+2\sqrt2$

---

这一期要介绍的是换底公式.

> $\log_bN=\frac{\log_aN}{\log_ab}$

证明过程和上期习题1答案差不多.

> 例题: 设56<sup>a</sup>=14, 试用a表示log<sub>7</sub>56 (一年多前的某日, 此题在某班红极一时)

首先, a=log<sub>56</sub>14

$\log_7 56=\frac{\log_2 56}{\log_2 7}=\frac{3+\log_2 7}{\log_2 7}$

所以要求的只有log<sub>2</sub>7.

$\log_2 7=\log_2 14-1=\frac{1}{\log_{14}2}=\frac{1}{\frac12\log_{4}4}-1=\frac{1}{\frac12(\log_{4}56-1)}-1=\frac{1}{\frac12(\frac{1}{a}-1)}-1=\frac{3a-1}{1-a}$

代入, 得到: $\log_7 56=\frac{2}{3a-1}$

练习题:

> 已知正实数x, y, z 满足3<sup>x</sup>=4<sup>y</sup>=6<sup>z</sup>.
>
> (1): 求证:$\frac{1}{z}-\frac{1}{x}=\frac{1}{2y}$
>
> (2): 比较3x, 4y, 6z 的大小.

