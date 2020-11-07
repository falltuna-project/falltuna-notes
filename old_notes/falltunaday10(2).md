求椭圆焦点三角形$PF_1F_2$面积

<img src="../img/day12/Screen Shot 5780-11-25 at 14.24.18.png" alt="Screen Shot 5780-11-25 at 14.24.18" style="zoom:30%;" />

已知: 椭圆 $\frac{x^2}{a^2}+\frac{y^2}{b^2}=1 (a>b), F_1, F_2$为椭圆两焦点, $\angle F_1PF_2=\theta$, 

求$S_{\triangle PF_1F_2}$

解: 设$PF_1=m, PF_2=n$

$\therefore m + n =2a$

在$\triangle PF_1F_2$中, 由余弦定理:

$F_1F_2^2 = PF_1^2 + PF_2^2-2PF_1\cdot PF_2\cdot\cos\theta$

$\therefore 4c^2 = m^2+n^2-2mn\cos\theta = (m+n)^2-2mn(1+\cos\theta)$

$\therefore 4c^2=4a^2-2mn(1+\cos\theta)$

$mn(1+\cos\theta) = 2a^2-2c^2=2b^2$

$\therefore mn = \frac{2b^2}{1+\cos\theta}$

$\therefore S_{\triangle PF_1F_2} = \frac12 PF_1\cdot PF_2\cdot \sin\theta = \frac12 mn\sin\theta = \frac{b^2\sin\theta}{1+\cos\theta}$

由三角比公式$\tan\frac\theta2=\frac{\sin\theta}{1+\cos\theta}$

$\therefore S_{\triangle PF_1F_2}=b^2\tan\frac\theta2$

