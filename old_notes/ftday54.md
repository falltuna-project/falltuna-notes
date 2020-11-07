# 那些学完就忘的立体几何#7 (线面夹角)
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
前几天的文章里介绍了空间里直线之间的位置关系, 又介绍了线面垂直, 现在我们来看看线面夹角这个概念.

#### 1º: l//α

定义 l与α夹角为0

#### 2º: l⟂α

定义l与α夹角为π/2

#### 3º: l∩α=O

<img src="../img/day54/Screen Shot 5781-01-14 at 18.01.12.png" alt="Screen Shot 5781-01-14 at 18.01.12" style="zoom:50%;" />

定义l与α夹角为∠POQ

**`(斜交于平面的直线与平面的夹角即为直线与直线在平面上射影的夹角)`**

---

接下来试着来证明下面这个结论:

<img src="../img/day54/Screen Shot 5781-01-14 at 20.04.50.png" alt="Screen Shot 5781-01-14 at 20.04.50" style="zoom:50%;" />

$$
\begin{cases}
PO\cap平面OHQ=O\\
PQ\perp 平面OHQ\\
QH\perp OH
\end{cases}\implies \cos\angle POH=\cos\angle POQ\cdot\cos\angle QOH
$$

证明过程如下: $设\angle POH=\alpha, \angle POQ=\beta, \angle QOH=\gamma$
$$
\left. \begin{gathered}
PQ\perp 平面OHQ\implies & HQ\perp PQ\\
& HQ\perp OH
\end{gathered} \right\}
\implies PH\perp OH
$$
(利用三垂线定理证明垂直)
$$
\cos\beta=\frac{OQ}{OP},\cos\gamma=\frac{OH}{OQ}
$$
$$
\cos\beta\cdot\cos\gamma=\cos\frac{OH}{OP}=\cos\alpha
$$
得证.

是不是很简单? 然而……这就是大名鼎鼎的**三余弦定理**(又称爪子定理、折叠角公式)

三余弦定理很有用, 具体例子见下期.

---

由于本期很短, 在这里随便啰嗦一点.

其实我到现在还没背出来三余弦定理, 而且这个结论说实话, 对于第七感比较弱的人很反直觉(反倒是三正弦定理对第七感弱的人比较友善).

看到这个推导过程, 可能有些人会说什么“不就是这么个破公式吗, 背是不用背的, 现场推导就行了!” 

公式这种东西, 其实是一个有用的模型. 正因为这个结论常用才会被作为公式. 试扪心自问, 能否背出三角比的升降幂公式? 我反正是背不出来的, 但因为知道升降幂公式的存在, 就知道了一种解题思路, 做题时回忆起来说不定就能解出题目.

其实出题老师说不定就是想着“啊这里出一道三余弦可以快速解决的题目吧……”就写下了一道题, 要是看到题目的时候还不回忆起三余弦, 就算会推导三余弦也没用了.

会推导公式固然是好的, 但也不能忘了条件和应用场景啊……(说的就是我)

