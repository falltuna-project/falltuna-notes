定义$\vec{OM}=(a,b)$的“相伴函数“为$f(x)=a\sin x + b\cos x (x\in \mathbb{R})$,

 向量$\vec{OM}=(a,b)$称为函数$f(x)=a\sin x + b\cos x$的“相伴向量”(其中$O$为坐标原点). 

记平面内所有向量的“相伴函数”构成的集合为$S$.

(1)设$h(x)=\cos(x+ \frac\pi6)-2\cos(x+\alpha)(\alpha \in \mathbb{R})$, 

求证: $h(x) \in S$, 并求$h(x)$的“相伴向量”模的取值范围;

---

(1) 分析: 既然要证明$h(x)$是$S$的元素, 那么只需要把$h(x)$化成$a\sin x + b\cos x$的形式即可. 关键是怎么做? 

原括号里有$ \frac\pi6$和$\alpha$作为参数, 使用**两角和差公式**应该可以把参数拆出来, 保留$\cos(x)$和$\sin(x)$

解: $h(x)=\cos x\cdot \cos \frac\pi6-\sin x\cdot \sin\frac\pi6-2\cos x\cos \alpha + 2\sin x \sin\alpha$

经过化简后得到: $h(x)=(2\sin\alpha - \frac12)\sin x + (\frac{\sqrt{3}}2 - 2\cos\alpha)\cos x$

$\therefore h(x)\in S$

那么“伴随向量”的模长取值范围也不难求了:

$\vec{OM}=(2\sin\alpha-\frac12,\frac{\sqrt3}2-2\cos\alpha)$

$|\vec{OM}|^2=4\sin^2\alpha+\frac14-2\sin\alpha+\frac34+4\cos^2\alpha-2\sqrt3\cos\alpha$

$\because \sin^2\alpha+\cos^2\alpha=1$

$\therefore |\vec{OM}|^2 = 5- 2(\sin\alpha+\sqrt{3}\cos\alpha)$

又$a\sin x+b\cos x = \sqrt{a^2+b^2}\sin(x+\arctan\frac ba)$

$\therefore |\vec{OM}|^2 = 5- 4\sin(\alpha+\frac\pi3)$

由于$\sin (x) \in [-1,1]$

$\therefore |\vec{OM}|^2\in[1,9]$

$\therefore |\vec{OM}|\in[1,3]$

小结: 应对这样的题目时, 应该先分析需要把式子化简成什么样子, 再使用公式变形. 同时也应该掌握**两角和公式**、**辅助角公式**以及三角函数的基本性质. (实际上**辅助角公式**可以现场推导, 但需要对“式子能化简到什么程度”有意识)

---

(秋天的金枪鱼- Day? 来自“秋天的金枪鱼”的“吃白巧克力的黑猫”)

如果对我们有什么建议, 或是有想了解的知识/题目, 请留言! 谢谢支持!