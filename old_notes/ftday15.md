今天我们来看一个有趣的极限:
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
$$ \lim\limits_{n\to\infty}(n\cdot\sin\frac{180^\circ}n) $$

方法一: 代数变换

 $\lim\limits_{n\to\infty}(n\cdot\sin\frac{180^\circ}n)$
 $=\lim\limits_{x\to 0}(\frac1x\cdot\sin(\pi x))$
 $=\lim\limits_{x\to 0}(\frac{\sin(\pi x)}{\pi x}\cdot\pi)$
 $=\pi\cdot\lim\limits_{x\to 0}(\frac{\sin(\pi x)}{\pi x})$
 $=\pi\cdot\lim\limits_{\pi\cdot x\to 0}(\frac{\sin(\pi x)}{\pi x})$

由极限 $\lim\limits_{x\to 0}(\frac{\sin x}x = 1)$ 得原式= $\pi\cdot1=\pi$ 

方法二: 几何意义

将180º的弧分为n份, $\sin\frac{180^\circ}n$表示的是图中所示的绿色线段长度, 而$n\cdot\sin\frac{180^\circ}n$则是n个绿色线段的长度.

<img src="../img/day15/Screen Shot 5780-11-29 at 23.46.15.png" alt="Screen Shot 5780-11-29 at 23.46.15" style="zoom:30%;" />

显然, 我们可以得出, 分割的份数n越大, 绿色线段总的长度就越接近圆弧的长度, 因此在n趋近于无穷大时, $n\cdot\sin\frac{180^\circ}n$ 就趋近于180º圆弧之长,即π. 