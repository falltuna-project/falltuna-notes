## 对数篇(3) 指数方程
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
上期答案:

(1)

设3<sup>x</sup>=k

$\frac{1}{x}+\frac{1}{2y}=\log_k3+\frac12\log_k4=\log_k3+\log_k2=\log_k6=\frac{1}{\log_6k}=\frac1z$

(2)

设3<sup>x</sup>=k

$\frac{3x}{4y}=\frac{3\log_3k}{4\log_4k}=\frac{\frac{3}{\log_k3}}{\frac{4}{log_k4}}=\frac{log_k64}{log_k81}<1$

同理4y<6z

所以3x<4y<6z

---

今天我要来介绍指数方程. 虽说如此, 由于个人原因, 那个年代的数学笔记全部丢失, 所以只能凭借精编了.

指数方程主要有以下几类:

* a<sup>x</sup>=b (a>0, a≠1, b>0)

方程的解为x=log<sub>a</sub>b

* a<sup>f(x)</sup>=a<sup>g(x)</sup> (a>0, a≠1)

在这种情况下, 直接求解f(x)=g(x)的解即可.

* A·a<sup>2x</sup>+B·a<sup>x</sup>+C=0 或 A·a<sup>2x</sup>+B·a<sup>x</sup>b<sup>x</sup>+Cb<sup>2x</sup>=0 (a,b>0, a,b≠1, a≠b)

换元, 令u=a<sup>x</sup>(或(a/b)<sup>x</sup>,在后一个例子中), 将原式化简为二次函数, 解之即可.

需注意的是只能保留正根(因为a<sup>x</sup>(或(a/b)<sup>x</sup>,在后一个例子中)作为真数必须大于0)

---

例题:

> 解关于x的方程:
>
> $\frac{a^x-a^{-x}}{a^x+a^{-x}}=b$

~~可能眼睛尖的同学已经发现了当a=e的时候这东西就是tanh(x)=b, 所以|b|≥1时无解~~

设u=a<sup>x</sup>,

经过一系列眩目的变形, 我们得到了: $u=\sqrt{\frac{1-b}{1+b}}$

显然, b∈[-1,1) 时无解, 而b=1时, u=0, 真数不大于0, 也无解.

于是当b∈(-∞, -1)∪(1, +∞), 有解

$x=\frac12\log_a\frac{1-b}{1+b}$

---

练习:

> 若关于x的方程2a·3<sup>-|x-1|</sup>-3<sup>-2|x-1|</sup>-2a-1=0有实数解, 求实数a的取值范围.