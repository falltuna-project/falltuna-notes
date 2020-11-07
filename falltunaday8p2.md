## 在解题过程中多用一些几何意义吧!

对有些人来说, 无论是在初中数学中还是高中数学中, 几何都有些烦人. 不过有时, 要解决代数问题, 我们也得联系几何意义. 下面是一道例题

---

定义非零向量$\vec{OM}=(a,b)$的“相伴函数“为$f(x)=a\sin x + b\cos x (x\in \mathbb{R})$,

 向量$\vec{OM}=(a,b)$称为函数$f(x)=a\sin x + b\cos x$的“相伴向量”(其中$O$为坐标原点). 

记平面内所有向量的“相伴函数”构成的集合为$S$.

(2)已知点$M(a,b)(b\neq0)$ 满足: $(a-\sqrt3)^2+(b-1)^2=1$上一点, 

向量$\vec{OM}$的“相伴函数”$f(x)$在$x=x_0$处取得最大值. 当点$M$运动时, 求$\tan2x_0$的取值范围.

---

先开始分析题目

观察可知,  $(a-\sqrt3)^2+(b-1)^2=1$是一个圆, 圆心在$(\sqrt3,1)$,半径为1, 所以$a\ge \sqrt3-1, b\gt0$

$f(x)$可以用**辅助角公式**化简为$\sqrt{a^2+b^2}\sin (x+\arctan\frac ba)$若要取到最大值, 一定是在$x+\arctan\frac ba=\frac\pi2+2k\pi$时,

$i.e. x_0=\frac\pi2-\arctan\frac ba + 2k\pi$, 显然$2k\pi$不影响正切值, 省略.

---

### 如果我们就这样开始计算……

那么既然得到了$x_0=\frac\pi2-\arctan\frac ba$, 就知道$2x_0=\pi - 2\arctan\frac ba$,

$\tan 2x_0=-\tan(2\arctan\frac ba)$, 那么根据正切两倍角公式, 不难得出$\tan2 x_0=\frac{-2\frac ba}{1-\frac{b^2}{a^2}}=-\frac{2ab}{a^2-b^2}$, 现在这个式子看起来好多了, 但考虑到我们对$a,b$的了解仅限上面那个复杂得要死的圆, 就算能化简出$a,b$的关系... (一看就知道有根号) 求这样一个式子的值域也是一件很困难的事.

---

### 如果多考虑点几何意义……

$M$点坐标是$(a,b)$,  $\frac ba$的意义是什么呢?

根据直线斜率的定义, $k_{OM}=\frac ba$

$M$既然在这个圆上, 

<img src="/Users/ngichingaij/Documents/falltuna_data/img/day8/Screen Shot 5780-11-22 at 17.23.19.png" alt="Screen Shot 5780-11-22 at 17.23.19" style="zoom:30%;" />

那斜率最小就是这种情况: $M$点在$x$轴正半轴上:$\frac ba=0$.

然而题目条件规定$(b\neq0)$, 也就是说:

$\therefore x_{0_{max}}=\frac\pi2-0 \lt\frac\pi2 $

看起来很顺利, 但是$x_{0_{min}}$怎么求呢?

我们知道从圆外一点引一条直线, 与圆有交点, 切点的斜率取到最大值或者最小值 (可以证明, 但这里直接用这个结论).

<img src="/Users/ngichingaij/Documents/falltuna_data/img/day8/Screen Shot 5780-11-22 at 17.41.27.png" alt="Screen Shot 5780-11-22 at 17.41.27" style="zoom:30%;" />

显然, 切线$OM\perp AM$,

$\therefore\triangle AOD\cong\triangle AOM (HL.)$

显然, 此时$x_{0_{max}}=\frac\pi2-\alpha_{OM}=\frac\pi2-2\cdot \frac\pi6 = \frac\pi6$

$\therefore x_0 \in [\frac\pi6, \frac\pi2)$

$\therefore 2x_0 \in [\frac\pi3, \pi)$

所以,$\tan2x_0\in (-\infty, 0)\cup[\sqrt3,+\infty)$

小结: 面对这种题目时, 可以使用**数形结合**的方法, 找到题目中的量的几何意义, 这也是做题时中常用的技巧.

---

(秋天的金枪鱼- Day8 来自“秋天的金枪鱼”的“吃白巧克力的黑猫”)

如果对我们有什么建议, 或是有想了解的知识/题目, 请留言! 谢谢支持!