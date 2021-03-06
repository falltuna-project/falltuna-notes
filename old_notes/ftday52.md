# 那些学完就忘的立体几何#5 (线面垂直)
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
经过了前几篇的折磨(目前我还不知道究竟前几篇有多困难, 毕竟我是先写本文再打算去补前几篇的), 本期我们来看一个相对轻松一些的话题——线面垂直.

## 线面垂直的定义

线面垂直, 顾名思义, 就是直线与平面垂直. ~~这好像是废话~~

其定义就是: **`直线与平面上 任意一条直线都垂直, 记号为l⟂α`**

~~第七感比较弱的同学可能对此感到奇怪, 为什么是任意一条直线? 平面上会有无数条直线和已知直线异面的? 但别忘了还有异面垂直这件事!~~

## 线面垂直的判定

我们不能指望用线面垂直的定义去证明线面垂直, 毕竟那可是要证明无数条直线垂直于已知直线啊! ~~地球毁灭了都证不完~~

所以, 下面是线面垂直的判定定理:

**`若已知直线垂直于平面上的两条相交直线, 则已知直线垂直于平面.`**
$$
\begin{cases}
a \subset \alpha\\
b\subset\alpha\\
a\cap b=M\\
l\perp a\\
l\perp b
\end{cases}
$$

$$
=>l\perp \alpha
$$



狂欢吧! 本来是无穷多条直线的工作量被简化成了两条直线! (虽说这两条直线有特殊条件限制)

~~不要吐槽这看起来很长, 因为等到熟练了以后~~如果你觉得a⊂α, b⊂α是显然的, 就可以不用写!

### 判定定理的证明

接下来要证明这个结论

~~学过空间向量的同学可以用空间向量秒杀, 但现在还是老老实实好好证明吧~~

∵a, b ⊂ α, a ∩ b = O

所以a,b都是α上的直线, 而且更棒的是他们不平行.

所以我们可以先把平面α分割成三个划分: A是所有平行于a(包括a)的直线的集合;  B是所有平行于b(包括b)的直线的集合; C是所有其他直线的集合.

l ⊥ a

=> ∀x∈A, x ⊥ l (等角定理)

同理∀y∈B, y ⊥ l

于是我们证明了A,B这两个子集的所有直线都平行于l

剩下的就只有C集合要处理了

~~这时候我恨不得使用空间向量分解定理, 可惜不行~~

从C中随便取出一条直线c, 在c上随便取一点Q. 在l上, 平面外取一点P.

过Q作直线, 使得QA=QB, 其中A∈a, B∈b, 联结AB, PA, PB, PQ.

PO⊥OA => PA²=AO²+PO²

同理PB²=BO²+PO²

又由于中线定理, 

2OQ²+1/2AB²=OA²+OB²

2PQ² +1/2AB²=PA²+PB²

把这四个式子加加减减, 最终竟然得到了PQ²=PO²+OQ², 

说明l确实垂直于c, 

既然对于任意的c都能如此操作

所以C中所有元素都垂直于l

得证.

当然网上还有用全等证明的方法, 那个的辅助线更多, 感兴趣的话可以上网查, 这里不写了.

---

有了线面垂直的判定定理, 我们可以判定线面垂直了.

注意! 平面上两条直线必须是相交的! 如果是平行的话会出事! ~~第七感好的同学估计已经想象出来了.~~

## 线面垂直的性质

线面垂直具有很多性质, 这些性质很实用(不如说没有这些性质, 就算你~~不小心~~证明线面垂直, 也没什么用)

### 线面垂直性质

**`如果一条直线垂直于一平面, 则该直线垂直于平面中的任意一条直线.`**

话说这是定义吧! 但无论是上课还是网上资料都把这个作为性质.

### 引理1

**`过已知平面外一点能且只能作一条直线垂直于平面.`**

好的接下来我们来证明. 

> 假设过点P可以作两条直线垂直于已知平面α, 分别为m和n.
>
> 假设两个垂足分别是A和B, 联结AB.
>
> 在三角形PAB中好像有两个直角啊, 矛盾了.
>
> 得证.

引理1也是个有用的性质, 更重要的是我们要用这个证明性质定理. (所以才叫引理)

### 引理2

**`两条平行直线中一条垂直于已知平面, 则另一条也垂直于已知平面.`**
$$
\begin{cases}
a\perp\alpha\\
b//a
\end{cases}
\implies b\perp\alpha
$$


> a, b 确立平面β. 设α∩β=l, b∩α=P
>
> 在平面β上, b⊥l
>
> 过P作直线c, c⊂α
>
> 由性质, a⊥c
>
> 由等角定理, b⊥c
>
> 又c∩l=P
>
> 所以b⊥α
>
> 得证

### 性质定理

**`两条垂直于同一平面的直线互相平行.`**

符号语言来说就是:
$$
\begin{cases}
m\perp\alpha\\
n\perp\alpha
\end{cases}
\implies m//n
$$
是个直观来说成立的结论, 但我们还是试着证明一下.

还是利用反证法.

> 1º 假设m∩n=P
>
> 那么过P点有两条垂直于平面α的直线, 与引理1矛盾.
>
> 2º 假设m和n是异面直线
>
> 从m上取一点Q,
>
> Q在直线n外, 所以经过Q和n可以确定一个平面β
>
> 过Q, 在β上作l//n
>
> 又n⊥α
>
> l⊥α (引理2)
>
> 于是过Q点有两条直线(m和l)垂直于平面α, 与引理1矛盾.
>
> 综合1º, 2º, m//n
>
> 得证

---

反证是一种很重要的证明方式, 尤其是在立体几何证明中. 当你忽然发现正面迎敌没有办法说明, 或者正面迎敌需要证明无数次的时候就可以试试看反证了.

这些就是线面垂直的重点内容了. 本期无作业~

