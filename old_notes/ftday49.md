# 那些学完就忘的立体几何#3 (直线与直线的位置关系)
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
在空间中呢, 直线与直线有三种关系:

## 相交

两条直线相交, 有一个交点.

## 平行

两直线没有交点, 而且存在一个平面同时包含两条直线.

## 异面

~~看到前面那敷衍的两句话, 其实本期关键就是异面.~~

不同在任何一个平面内的两直线叫做异面直线.

### 异面直线判定定理

要证明两条直线不在同一平面上, 直接用定义的话岂不是要把空间里每一个平面都找一遍? 怎么可能找得完? 所以这时候我们需要借助的是异面直线的判定定理.

**`交于平面的一直线与平面上不过此交点的直线异面.`**
$$
\begin{cases}
m\cap\alpha=P\\
n\subset\alpha\\
P\notin n
\end{cases}
\implies m与n异面
$$
判定定理友善多了, 但我们需要证明满足判定定理所示条件时, 两直线真的异面(即满足定义)

接下来是对判定定理的证明.

> 假设存在平面β使得m,n⊂β
>
> 任取Q∈m, Q≠P
>
> 那么有Q∉α和Q∈β.
>
> 已知P∈β, n⊂β, 又P∈α, n⊂α.
>
> 所以α和β重合(公理3推论2)
>
> 所以有Q∈α, 但已知Q∉α. 矛盾. 所以不存在平面β使得m,n⊂β, 证毕.

---

## 空间中直线所成角

首先, 我们先定义两平行直线所成的角是0.

相交直线的夹角很容易定义, 但如何定义异面直线所成角呢?

假设我们有异面直线a和b, 过空间内任意点P, 作a'//a, b'//b, 这时, a'与b'所成的锐角或者直角, 就是“异面直线a与b所成的角”

当a'与b'所成角为90º时, 那么就称异面直线a与b垂直.

## 异面直线的距离

有且仅有一条直线垂直于两异面直线(我不会证明), 此线即称为异面直线的公垂线.

公垂线与两异面直线的两交点所成的线段即称为公垂线段, 而公垂线段的长度就是异面直线的距离.

## 空间四边形

四条线段拼接起来, 首尾相连, 四个顶点不共面, 这种图形就叫**空间四边形**. 典型的例子是: 把一张A4纸沿对角线折一下, 然后放在书桌上. 因为折了一下所以有一点会不在桌面上(四点不共面), 此时它还是四边形, 但就是空间四边形了.

从两条异面直线上各取两点, 就能组成一个空间四边形, 后面的题目里经常会有的.

