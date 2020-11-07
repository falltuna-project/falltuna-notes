## 对数篇(1) 对数的定义
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
对数是指数的逆运算. 

传说古代法国贵族把对数运算作为消遣方式. 对数距离我们的生活很近, 在日常生活中也经常出现对数, 如pH、分贝数、半衰期~~以及我们的数学考卷中~~.

对数的定义如下:

在a>0, 且a≠1, 且 N>0的条件下, 唯一满足a<sup>x</sup>=N(称为**真数**)的数x, 称为N以a为**底**的**对数**, 以符号log<sub>a</sub>N表示. 当a=2时, 一般写作lbN(虽说如此, 从未见过有人这么写); 当a=e时, 一般写作lnN; 当a=10时, 一般写作lgN(或者logN)

log<sub>a</sub>N也只是在20世纪才出现的, 所以如果你能发明一套更完善的表示对数的符号, 如果流行起来了也能进未来的教科书呢!

有了这个定义以后, 我们可以开始计算了:

> 例1:
>
> log<sub>5</sub>5√5+lne

根据log的定义, 5的多少次方是5√5呢? 显然是1.5次.

那lne是多少呢? 显然是1.

所以原式=2.5

接下来来介绍对数的运算性质

---

 log<sub>a</sub>MN=log<sub>a</sub>M+log<sub>a</sub>N

证明如下:

设μ=log<sub>a</sub>M,ν=log<sub>a</sub>N

=>M=a<sup>μ</sup>, N=a<sup>ν</sup>

∴MN=a<sup>μ+ν</sup>, log(MN)=μ+ν=log<sub>a</sub>M+log<sub>a</sub>N

同理可得:

$\log_a\frac MN=\log_aM-\log_aN$

---

 log<sub>a</sub>M<sup>c</sup>=c log<sub>a</sub>M

证明如下:

设μ=log<sub>a</sub>M, M<sup>c</sup>=a<sup>μc</sup>, ∴log<sub>a</sub>M<sup>c</sup>=log<sub>a</sub>a<sup>μc</sup>=μc=c log<sub>a</sub>M

---

由上面两个, 我们可以看出其实对数可以把乘法除法转换为加法减法, 把乘方转化为减法.

有了这两个性质, 在计算对数时我们可以自由转换真数的值.

练习:

> (1)利用已知性质(不用换底公式), 证明log<sub>a</sub>b·log<sub>b</sub>a=1
>
> (2)$2\lg\frac{x-y}{2}=\lg x+\lg y$,求$\frac xy$



