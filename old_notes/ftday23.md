数学归纳法
<script 
  src="https://cdn.bootcss.com/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML"></script>
$a_1,a_2,...a_n$是正实数列.

满足: $a_{n+1}\ge\frac{na_n}{a_n^2+n-1}$

求证:$\sum_{i=1}^n a_n\ge n$

---

按照数学归纳法的套路, 我们应该先证明n=1的情况是满足条件的, 如下:

$1^\circ:$
$$
a_2\ge\frac{a_1}{a_2}=\frac1{a_1}
a_1+a_2\ge a_1+\frac{1}{a_1}\ge2
$$
其中第一个大于等于号来自题目条件, 第二个是利用基本不等式得到的.

---

接下来, 假设n=k(k≥2)时原数列满足求证内容, 我们要证明n=k+1时也满足.

$2^\circ$:
$$
\sum_{i=1}^k a_i\ge k
$$
两种情况: 

第一种, $a_{k+1}\gt1$时, 必定成立.

第二种, $0<a_{k+1}\le1$, 我们重点讨论这种情况:

好的, 现在……

我们把条件的式子两边取倒数(我根本想不到这一步):
$$
\frac{1}{a_{k+1}}\le\frac{a_k^2+k-1}{ka_k}
$$
这一步骤的本质是什么呢? 我仔细想想, 是把数列项最高次+多项式转移到分子上, 方便运算.

左右乘以k, 得到:
$$
\frac{k}{a_{k+1}}\le\frac{a_k^2+k-1}{a_k}=a_k+\frac{k-1}{a_k}
$$
再移项, 得到:
$$
a_k\ge\frac{k}{a_{k+1}}-\frac{k-1}{a_k}
$$
这是可能是关键一步, 但如果缺乏练习根本想不出这一步. 仔细一想我接触的大多数数列题的套路都是把$a_{k+1}$与$k+1+i$集中在同一个项里, 把$a_{k}$与$k+i$集中在另一个式子里(大致如此).

老师讲解到这里, 我觉得它可以裂项, 而且更幸运的是k-1=0, 所以:
$$
\sum_{i=1}^k a_i \ge \frac{k}{a_{k+1}}
$$


那么, 
$$
\sum_{i=1}^{k+1} a_i \ge \frac{k}{a_{k+1}}+a_{k+1}
$$
为什么要单独拆出$a_{k+1}$呢? 我觉得是因为:

* 题目已知$\sum_{i=1}^k a_i\ge k$这一条件, 如果不单独拆出来就不能利用
* 如果不拆出来, 就会引入新的$a_{k+2}$

我们可以利用耐克函数的性质: 

当$a_{k+1}\le\sqrt k$时, 右边的式子单调递减.

又由于$a_{k+1}\in(0,1]$, 且$\sqrt k\ge\sqrt2,$ 所以右边的式子最小值在$a_{k+1}=1$时取到. 

因此, 我们有
$$
\sum_{i=1}^{k+1} a_i \ge \frac{k}{a_{k+1}}+a_{k+1}\ge k+1
$$
所以,若:$\sum_{i=1}^k a_i\ge k$成立, 则$\sum_{i=1}^{k+1} a_i \ge k+1$成立.

综合$1^\circ,2^\circ$,有对于正实数列$a_1,a_2,...a_n$, 若满足 $a_{n+1}\ge\frac{na_n}{a_n^2+n-1}$

则$\sum_{i=1}^n a_n\ge n$成立.

