# 那些学完就忘的立体几何#2 (四条公理与等角定理)
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
所谓公理, 就是那种不证自明的, 理所应当的命题.

现在这一期要介绍的就是立体几何中的几个公理以及重要的等角定理.

## 公理1

`如果一条直线上的两点在一个平面内，那么这条直线上的所有点都在这个平面内.`

用集合语言来表示就是:
$$
\begin{cases}
A,B \in a\\
A,B \in \alpha\\
\end{cases}
\implies a\subset\alpha
$$


说实话, 我根本举不出反例.

## 公理2

`如果两个平面有一个公共点，那么它们无数多个公共点，且所有公共点的集合是一 条经过该公共点的直线.`

用集合语言来表示就是:
$$
\begin{cases}
P \in \alpha\\
P \in \beta\\
\end{cases}
\implies \alpha \cap \beta = l, P\in l
$$
说实话, 我还是举不出反例.

## 公理3

公理3就很重要了, 尤其是公理3的3个推论. 有了它们, 我们才能确定平面, 才能作辅助平面.

`经过不在同一条直线上的三点有且只有一个平面.`

(或者可以称作是: `三个不共线的点确定一个平面`)

`推论一: 经过一条直线和直线外的一点有且只有一个平面.`

已经是直线外一点了, 肯定三点不共线, 所以根据公理3, 过一条直线和直线外的一点可以确定平面.

`推论二: 经过两条相交直线有且只有一个平面.`

取交点A, 再从两条直线上分别取一点B, C. 

C在直线AB外, 因为推论一成立所以这个也一定成立.

`推论三: 经过两条平行直线有且只有一个平面.`

其证明和推论二差不多.

## 公理4

可以认定是平行的传递性.

`平行于同一条直线的两条直线互相平行.`

可以说是废话了, 但其实立体几何届很多看似成立的结论……其实也成立, 但我们从来没证明过, 所以需要证明才能使用.

为什么要这么做呢? 因为还有一些看似成立的结论实则是经不起推敲的. ~~第七感比较强的人可能马上就能举出反例, 但如果第七感不够强的话,~~ 乱写过程很容易给自己招致麻烦.

## 等角定理

`如果一个角的两边和另一个角的两边分别平行，那么这两个角相等(或互补).`

“或互补” 很重要! 毕竟确实有可能互补(在后面会出现很多变态的“求异面直线夹角”类型的题目, 夹角一定是锐角(或直角), 但是通过平行直线转换过去的那个角搞不好可能是钝角呢?)

~~第七感强的同学如果能直接想象出两个角的大小关系的话可以省略括号.~~

## 总结

以上就是立体几何基础的部分, 有了这些工具, 接下来就是要对付难缠的立体几何题了!

