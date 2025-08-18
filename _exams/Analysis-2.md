---
title: "数学分析II"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-2
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
---
主讲：苗俊杰副教授，戴浩辉副教授

<details markdown="1">
  <summary> 2024春季学期第三次小测</summary>
  
**第1题[20分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. 若非负无穷积分\\(\displaystyle\int_a^{+\infty} f(x)\ \mathrm{d}x\\)收敛且\\(f(x)\\)在\\([a,+\infty)\\)上连续，则\\(\lim\limits_{x\to+\infty}f(x)=0.\\)
2. 若无穷积分\\(\displaystyle\int_a^{+\infty} f(x)\ \mathrm{d}x\\)绝对收敛，则无穷积分\\(\displaystyle\int_a^{+\infty} f^2(x)\ \mathrm{d}x\\)也收敛.
3. 若正项级数\\(\sum u_n\\)收敛，则\\(\ \exists\ N,\ n>N\\)时\\(\sqrt[n]{u_n}<q\\)，其中\\(q\in [0,1).\\)
4. 若对任意\\(p\in\mathbb{N}_+,\forall\varepsilon>0,\ \exists\ N\in\mathbb{N}_+\\)，当\\(n_N\\)时，\\(\|u _{n+1}+u _{n+2}+\cdots +u _{n+p}\|<\varepsilon\\)，则\\(\sum u_n\\)收敛.

**第2题[20分]** 讨论下列反常积分的敛散性（绝对收敛、条件收敛或发散）
1. \\(\displaystyle\int_1^{+\infty} e^{-x}\arccos x \ \mathrm{d}x\\);
2. \\(\displaystyle\int_0^1 \frac{\sqrt{x}}{e^{x^2}-1} \ \mathrm{d}x\\);
3. \\(\displaystyle\int_0^1 \frac{\ln(1+\sin x)}{x^p}\ \mathrm{d}x,(p>0)\\);
4. \\(\displaystyle\int_0^{+\infty} \frac{\cos(x^2)}{(1+x)^p} \mathrm{d}x\\).

**第3题[20分]** 讨论下列数项级数的敛散性（绝对收敛、条件收敛或发散）
1. \\(\displaystyle\sum \frac{(-1)^nn^3}{3^n}\\);
2. \\(\displaystyle\sum \frac{(2n+1)!!}{(2n)^n} \\);
3. \\(\displaystyle\sum \frac{\sin 2n}{\sqrt{n}}\\);
4. \\(\displaystyle\sum \frac{1}{\ln((n+1)!)} \\).

**第4题[10分]** 设函数\\(f(x)\\)在\\([1,+\infty\\)上非负递减，若\\(\displaystyle\int_1^{+\infty}x^2f(x)\ \mathrm{d}x\\)收敛，证明\\(\lim\limits_{x\to+\infty}x^3f(x)=0.\\)

**第5题[10分]** 设数列\\(\\{a_n\\}\\)单调递减收敛于0，证明\\[\sum (-1)^n\sqrt[n]{a_1a_2\cdots a_n}\\]
收敛.

**第6题[10分]** 设正项级数\\(\displaystyle\sum_{n=1}^\infty a_n\\)收敛，余项\\(\displaystyle R_n=\sum_{k=n+1}^\infty a_k\\). 证明\\(\displaystyle\sum_{n=1}^\infty\frac{a_{n+1}}{\sqrt{R_n}}\\)收敛.

**第7题[10分]**证明Bertrand判别法：若正项级数\\(\sum u_n\\)满足
\\[\lim_{n\to\infty}\ln(n+1)\left[(n+1)\left(1-\frac{u_{n+1}}{u_n}\right)-1\right]=b,\\]
则当\\(b>1\\)时\\(\sum u_n\\)收敛，当\\(b<1\\)时\\(\sum u_n\\)发散.

</details>

<details markdown="1">
  <summary> 2025春季学期第一次小测</summary>
  
**第1题[28分]** 判断下列陈述是否正确，并简述理由（判断4分，理由3分）
1. 设数列\\(\\{a_n\\},\\{b_n\\}\\)均有界，则
\\(\varliminf\limits_{n\to\infty} (a_n+b_n)=\varliminf\limits_{n\to\infty} a_n+\varliminf\limits_{n\to\infty} b_n.\\)
2. 若数列\\(\\{a_n\\}\\)有界，\\(\varlimsup\limits_{n\to\infty}a_n>0\\)，则\\(\ \exists\ N\\)，当\\(n>N\\)时，\\(a_n>0.\\)
3. 若定义在\\(\mathbb{R}\\)上的连续函数\\(f(x)\\)是周期函数，则\\(f(x)\\)的原函数\\(F(x)\\)一定是周期函数.
4. 若定义在\\(\mathbb{R}\\)上的连续函数\\(f(x)\\)是偶函数，则\\(f(x)\\)的原函数\\(F(x)\\)一定是奇函数.

**第2题[16分]** 求以下数列的上下极限：
1. \\(\left\\{\dfrac{n}{n+1}2^{(-1)^n}\right\\}\\);
2. \\(\left\\{\sin\dfrac{n\pi}{3}\right\\}\\);
3. \\(\left\\{\sqrt[n]{n}\ln\dfrac{n+1}{n}\right\\}\\);
4. \\(\\{\sin n\\}\\).

**第3题[32分]** 计算以下不定积分
1. \\(\displaystyle \int (x+1)e^{x^2+2x+1}\ \mathrm{d}x\\)；
2. \\(\displaystyle \int \frac{\mathrm{d}x}{\sqrt{x}+\sqrt[3]{x}}\\)；
3. \\(\displaystyle \int \frac{ \mathrm{d}x}{2+\sin x}\\)；
4. \\(\displaystyle \int \frac{\mathrm{d}x}{x(x+1)(x^2+2x+2)}\\).

**第4题[12分]** 证明，若数列\\(\\{ a_n\\}\\)有界，\\(\varliminf\limits_{n\to\infty} a_n>0\\)，则\\(\exists~N\\)，当\\(n>N\\)时，\\(a_n>0.\\)

**第5题[12分]** 证明，若数列\\(\\{ a_n\\}\\)有界，则\\(A=\varlimsup\limits_{n\to\infty}a_n\\)的充要条件是\\(A=\inf\limits_{n}\sup\limits_{k\ge n}\\{a_k\\}\\).

</details>

<details markdown="1">
  <summary> 2025春季学期第二次小测</summary>
  
**第1题[20分]** 计算下列定积分
1. \\(\displaystyle \int_{-1}^4 \cos x e^{\sin x}\ \mathrm{d}x\\);
2. \\(\displaystyle \int_{-2}^2 x\cos^4x\ \mathrm{d}x\\);
3. \\(\displaystyle \int_0^1 \frac{\mathrm{d}x}{(1+x^2)^2}\\);
4. \\(\displaystyle \int_2^3  x\ln x\ \mathrm{d}x\\).

**第2题[30分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. 若函数\\(f(x)\\)在\\([a,b]\\)上可积，则存在\\(\xi\in[a,b]\\)，使得\\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x=f(\xi)(b-a).\\)
2. 若\\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x\ge 0\\)，则\\(f(x)\ge 0,\forall x\in[a,b].\\)
3. 若函数\\(f(x)\\)在\\([a,b]\\)上可积，则\\(F(x)=\displaystyle\int_a^x f(t)\ \mathrm{d}t\\)可导.
4. 若函数\\(\|f(x)\|\\)在\\([a,b]\\)可积，则\\(f(x)\\)在\\([a,b]\\)上可积.
5. 定积分\\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x\\)的几何意义是由直线\\(x=a,x=b,x\\)轴以及曲线\\(y=f(x),x\in[a,b]\\)所围成的平面图形的面积.
6. 若\\(f(x)\\)在\\([a,b]\\)上可积且\\(f(x)\neq 0,\forall x\in[a,b]\\)，则\\(\dfrac{1}{f(x)}\\)在\\([a,b]\\)上也可积.

**第3题[10分]**
1. 求第一象限中由极坐标曲线\\(r=\sqrt{3}\sin \theta,r=\cos\theta\\)所围成的平面图形的面积.
2. 求曲线\\(C:\begin{cases}x(t)=t-t^2\\\y(t)=1+\dfrac{4\sqrt{2}}{3}t^{\frac{3}{2}}\end{cases},t\in[0,1]\\)的弧长.

**第4题[10分]** 
1. \\(\displaystyle f(x)=\int_{\arcsin x}^{\ln(x+1)}e^{-t^2}\ \mathrm{d}t,x\in\left[\frac{1}{2},1\right]\\)，求\\(f'(x)\\);
2. 求极限\\(\lim\limits_{x\to 0}\dfrac{\int_{2x}^{x^2}tf(t)\ \mathrm{d}t}{x^2}\\)，其中\\(f\\)为\\(\mathbb{R}\\)上的连续函数.

**第5题[10分]** 计算由直线\\(x=4,x\\)轴以及曲线段\\(y=\sqrt{x},x\in[0,4]\\)所围平面图形绕\\(y\\)轴旋转一周所得旋转体的体积.

**第6题[10分]** 计算由曲线段\\(y=\sqrt{x},x\in[0,4]\\)绕\\(x\\)轴旋转一周所得的旋转曲面的面积.

**第7题[10分]** 设\\(f\\)在\\([0,1]\\)上连续可微，\\(0\le f'(x)\le 1,\ \forall x\in[0,1],\ f(0)=0.\\)，证明\\[\left(\int_0^1 f(x)\ \mathrm{d}x\right)^2\ge\int_0^1[f(x)]^3\ \mathrm{d}x,\\]且等号仅在\\(f(x)=x\\)或\\(f(x)\equiv 0\\)时成立.

</details>

<details markdown="1">
  <summary> 2025春季学期第三次小测</summary>
  
**第1题[20分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. 若\\(f(x)\le g(x),\forall x\in[a,+\infty)\\)，无穷积分\\(\displaystyle\int_a^{+\infty}g(x)\ \mathrm{d}x\\)收敛，则无穷积分\\(\displaystyle\int_a^{+\infty}f(x)\ \mathrm{d}x\\)收敛.
2. 若非负无穷积分\\(\displaystyle\int_a^{+\infty}f(x)\ \mathrm{d}x\\)收敛，则\\(\ \exists\ p>1\\)，使得极限\\(\lim\limits_{x\to+\infty}x^p f(x)\\)存在.
3. 若\\(u_n>0,\forall n\\)，数项级数\\(\sum u_n\\)收敛，则\\(\ \exists\ N,\ n>N\\)时\\(\dfrac{u_{n+1}}{u_n}\le q\\)，其中\\(q\in [0,1)\\).
4. 若\\(u_n\ge 0,\forall n\\)，且\\(\ \exists\ N\in\mathbb{N}_+\\)，当\\(n>N\\)时，\\(\sqrt[n]{u_n}<1\\)，则\\(\sum u_n\\)收敛.

**第2题[10分]** 计算下列反常积分的值：
1. \\(\displaystyle \int_1^{+\infty}e^{-x}\cos x\ \mathrm{d}x\\);
2. \\(\displaystyle\int_0^2\frac{1}{x^{\frac{2}{3}}}\ \mathrm{d}x\\).

**第3题[10分]** 计算下列数项级数的和：
1. \\(\displaystyle\sum_{n=1}^\infty\frac{2+(-1)^n}{4^n}\\);
2. \\(\displaystyle\sum_{n=1}^\infty\frac{n}{(n+1)(n+2)(n+3)}\\).

**第4题[10分]** 讨论下列反常积分的敛散性：
1. \\(\displaystyle\int_1^{+\infty}\frac{x^2}{2^x}\ \mathrm{d}x\\);
2. \\(\displaystyle\int_0^1\frac{\arctan x}{\sqrt{x}\ln(1+x)}\ \mathrm{d}x\\).

**第5题[10分]** 讨论下列数项级数的敛散性：
1. \\(\displaystyle\sum_{n=1}^\infty\frac{1}{2^{\ln n}}\\);
2. \\(\displaystyle\sum_{n=2}^\infty\frac{1}{\sqrt{n}+(-1)^n}\\).

**第6题[10分]** 证明瑕积分\\(\displaystyle\int_0^1\frac{\ln x}{x^p}\ \mathrm{d}x\\)当\\(0<p<1\\)时收敛.

**第7题[10分]** 证明数项级数\\(\displaystyle\frac{(-1)^n\sin n}{n}\\)条件收敛. 

**第8题[10分]** 证明反常积分\\[\int_0^{+\infty}\frac{\sin x}{(x-\ln x)^p}\ \mathrm{d}x\\]
当\\(p>1\\)时绝对收敛，当\\(0<p\le 1\\)时条件收敛.

**第9题[10分]** 设\\(\\{a_n\\}\\)为单调递增无界的数列，且\\(a_1>0\\)，令\\[u_n=\frac{a_{n+1}-a_n}{a_n^pa_{n+1}}.\\]
证明：当\\(p>0\\)时，级数\\(\sum u_n\\)收敛.

</details>
