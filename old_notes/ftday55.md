# 那些学完就忘的立体几何#8 (三余弦定理)
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
上节课我们认识了三余弦定理, 现在是见识三余弦之威力的时刻.

---

例题1: P为Rt△ABC所在平面α外一点, ∠ACB=90º (如图)

若PC=a, ∠PCA=∠PCB=60º, 求P到α的距离及PC和α所成的角.

<img src="../img/day55/Screen Shot 5781-01-14 at 20.45.03.png" alt="Screen Shot 5781-01-14 at 20.45.03" style="zoom:30%;" />

还记得前几天的“精编三步”吗? ~~不记得的话也没关系~~

首先, “作”. 你觉得直线PC在平面上的射影是哪条线呢? 反正我觉得是∠ACB平分线.

接下来是“证”

本人的证法如下:

~~不妨设AC>BC~~

<img src="../img/day55/Screen Shot 5781-01-14 at 21.33.21.png" alt="Screen Shot 5781-01-14 at 21.33.21" style="zoom:30%;" />

在AC上取Q, 使得CQ=CB, 联结BQ (似乎是凑成了一个等腰直角三角形), 取中点M, 联结CM

显然∠QCM=∠BCM, 易证△PCB≌△PCQ⇒△PBM≌△PQM⇒PM⟂BQ, 又BQ⟂CM

所以BQ⟂平面PCM

平面PCM与α交线是CM, 作PF⟂CM延长线, 垂足为F

由线面垂直性质1, PF⟂BQ, 又PF⟂CM, CM∩BQ=M, 所以PF⟂α, 又F∈CM, 所以……

终于证明了本人的猜想是正确的(CM是PC在α上的射影)

最后一步是“算”

cos∠PCF·cos∠BCM=cos∠PCB

所以, ∠PCF=π/4

练习: 若PA=PB=PC, AC=18, P到α的距离为40, 求P到BC的距离 (不提供过程和答案, 毕竟最麻烦的证明已经结束了)

---

例题2: **在正方体ABCD-A₁B₁C₁D₁中, E,F分别为BC, A₁D₁中点(如图), 求AD与平面B₁EDF所成角的余弦值.**

<img src="../img/day55/Screen Shot 5781-01-14 at 18.19.29.png" alt="Screen Shot 5781-01-14 at 18.19.29" style="zoom:50%;" />

还是精编三步:

第一步是要**作**出AD在B₁EDF上的射影(~~一般是靠第七感~~)

<img src="../img/day55/Screen Shot 5781-01-14 at 18.29.50.png" alt="Screen Shot 5781-01-14 at 18.29.50" style="zoom:20%;" />→<img src="../img/day55/Screen Shot 5781-01-14 at 18.27.17.png" alt="Screen Shot 5781-01-14 at 18.27.17" style="zoom:20%;" />



~~第七感极强的同学脑子里可能会有这样的画面~~

所以可以看出AD在B₁EDF上的射影在直线DB₁上. ~~恐怕这不需要太多第七感~~

第二步, 证明AD在B₁EDF上的射影它真的在DB₁上.

这都好办~~(并不是某化学老师说的)~~

所以接下来就留给同学们证明. (三余弦定理, 不提供过程)

这次来说一下计算吧!

~~删掉第七感为你带来的图, 回到原图,~~ 联结AB₁
$$
\begin{cases}
A_1B=\sqrt{2}\\
AD=1\\
B_1D=\sqrt{3}
\end{cases}\implies \cos\angle ADB_1=\frac{\sqrt{3}}{3}
$$
显然, 用余弦定理可以解决此题的计算.

---

不得不说, 写最近3篇太累了.~~尤其是对于背不出三余弦的我.~~

写立体几何很麻烦. 不信看下面那张图(保留一切作图痕迹版) ~~GeoGebra的直线默认粗细是5, 不能忍, 每一根直线都得手动调到3的粗细, 不可理喻……~~ 

<img src="../img/day55/Screen Shot 5781-01-14 at 21.36.49.png" alt="Screen Shot 5781-01-14 at 21.36.49" style="zoom:30%;" />

然后LaTeX的话也就那样(落泪), 几何的LaTeX也没比代数复杂多少(代数: 一个不等式你可以写2行字). 一开始可能对\iff, \implies, \perp这些新符号不熟悉, 时间长了自然也就记住了. 但写推出过程时的排版还是挺讨厌的.

<img src="../img/day55/Screen Shot 5781-01-14 at 21.37.36.png" alt="Screen Shot 5781-01-14 at 21.37.36" style="zoom:50%;" />

~~立体几何图用电脑画多了审美观都刷新了. 救命! 我忍受不了我的作业本了!~~

希望各位大佬们可以来投稿, 给本人放个假. 

只要有5个人每周提供一道题目, 我就可以轻松一些了~~一周就只需要肝一天了, 剩下的时间可以用来开发金枪鱼官方平台.~~ 

因为官方平台~~将会~~支持Markdown (以及附带的 LaTeX、Mermaid Graph、Flowchart、HTML Tags), 所以投稿的时候也可以轻松一些了. ~~我们又不是写论文的, 为什么要用Word这种精甚的高档货呢?~~

**一周最优秀的投稿者有机会(指在运输范围内)可以获得金枪鱼(油浸, 185克)一罐!(我除外, 反正本来就是我的罐头)**

