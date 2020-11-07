## 对数篇(4) 对数方程
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
上期解答:

设u=3<sup>-|x-1|</sup>, 由此可得u∈(0,1], 讨论f(u)=2au-u<sup>2</sup>-2a-1(即原式)与u轴交点即可求出a的范围. a∈(-∞, -1/2)

---

本期我们来看对数方程.

> (1)log<sub>a</sub>f(x)=b (a>0, a≠1)

我们可以把它化简为f(x)=a<sup>b</sup>, 需要验算

> (2)log<sub>a</sub>f(x)=log<sub>a</sub>g(x) (a>0, a≠1)

我们可以把它作为f(x)=g(x)来处理, 但解x=x<sub>0</sub>要满足f(x<sub>0</sub>)>0, g(x<sub>0</sub>)>0

> (3)Alog<sub>a</sub><sup>2</sup>x+Blog<sub>a</sub>x+C=0 (a>0, a≠1)

换元, 需要验算.

---

我们来看一道例题:

> 若关于x的方程lg2x·lg3x=-a<sup>2</sup>, 有两个相异实数根, 求a的取值范围以及两根之积.

乍一看两个对数相乘似乎无可奈何, 但实际上这两个对数还能再拆.

lg2x·lg3x=(lgx+lg2)(lgx+lg3)=lg<sup>2</sup>x+(lg6)lgx+lg2·lg3=-a<sup>2</sup>

=>lg<sup>2</sup>x+(lg6)lgx+lg2·lg3+a<sup>2</sup>=0

于是乎这就是(3)类对数方程了, 换元, 以其判别式大于0, 得:

lg<sup>2</sup>6-4(lg2·lg3)a<sup>2</sup>>0

于是a的范围可以求出(由于表达式复杂, 不写了),

两根之积, 把a=0(在a的取值范围中)代入, lg2x·lg3x=0, x<sub>1</sub>=1/2,  x<sub>2</sub>=1/3, 所以两根之积等于1/6.

---

练习:

> 若关于x的方程log<sub>2</sub>x+1=2log<sub>2</sub>(x-a)恰有一个实数根, 求实数a的取值范围.

