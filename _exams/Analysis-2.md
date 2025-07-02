---
title: "数学分析II"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-2
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
---
主讲：某教授

## 2025春季学期期中考试

**第1题[15分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. \\([a,b]\\)上的任意单调函数一定在\\([a,b]\\)上Riemann可积；
2. 如果数项级数\\(\sum u_n\\)绝对收敛，则\\(\sum u_n^{2024}\\)绝对收敛. 如果数项级数\\(\sum u_n\\)收敛，则\\(\sum u_n^{2024}\\)收敛；
3. 设\\(\mathbb{R}^+\\)上的三个局部Riemann可积函数满足\\(h\le f\le g\\)，那么
   \\[\int_0^\infty h(x)\mathrm{d}x\text{和} \int_0^\infty g(x)\mathrm{d}x\text{收敛}\Rightarrow \int_0^\infty f(x)\mathrm{d}x\text{收敛}.\\]

**第2题[10分]** 证明\\(\displaystyle\sum_{n=3}^\infty\frac{2n-1}{n^3-4n}\\)收敛并求和.

**第3题[15分]** 记\\(h(x)=x\arctan(\dfrac{x-1}{x+1})\\). 确定\\(h\\)的定义域\\(D_h\\). 计算\\(h\\)的原函数. 求\\(\displaystyle\int_{-\sqrt{3}}^0h(x)\mathrm{d}x.\\)

**第4题[10分]** 设\\(a\neq 0\\)是实数. 根据\\(a\\)的取值，确定级数\\(\displaystyle\sum_{n=2}^\infty\frac{(-1)^n\sqrt{n}}{n^a+(-1)^n}\\)的敛散性.

**第5题[20分]** 设\\(\displaystyle f_n(x)=\frac{n(x^2+x)e^{-x}}{nx+1}\\)，任给\\(n\ge 0,x\in\mathbb{R}_+=[0,+\infty)\\).
1. 证明\\(f_n\\)在\\(\mathbb{R}_+\\)上逐点收敛，并求出\\(f_n\\)的逐点收敛极限函数\\(f\\).
2. 证明\\(f_n\\)在\\((0,+\infty)\\)上内闭一致收敛.
3. 证明\\(\displaystyle\lim_{n\to\infty}\int_0^\infty f_n(x)\mathrm{d}x\\)存在，并求出其极限值.

**第6题[20分]** （Rabbe判定）设\\((u_n),(v_n)\\)是两个严格正的实数序列，设
\\[\frac{u_{n+1}}{u_n}\le\frac{v_{n+1}}{v_n},\forall n\ge n_0\\]
1. 证明\\(\sum v_n\\)收敛时，\\(u_n\\)收敛.
2. 设\\(u_n\\)满足
\\[\lim_{n\to\infty}n\left(1-\frac{u_{n+1}}{u_n}\right)=\alpha\in\mathbb{R}\\]
证明若\\(\alpha>1\\)，则\\(\sum u_n\\)收敛；若\\(\alpha<1\\)，则\\(\sum u_n\\)发散.
3. 求级数\\(\displaystyle\sum_{n=1}^\infty\frac{n!}{(2x^2+1)(2x^2+2)\cdots(2x^2+n)}\\)的收敛域.

**第7题[10分]** 设\\((f_n)\\)是区间\\(I=[a,b]\\)上的一列连续函数，证明\\(f_n\\)在\\(I\\)上一致收敛到\\(f\\)当且仅当以下性质成立：
\\[\text{任给}I\text{中收敛序列}(x_n),\text{即}x_n\in I,\lim_{n\to\infty}x_n=x;\text{则}\lim_{n\to\infty}f_n(x_n)=f(x).\\]

**第8题[10分]** 设\\(f\\)是\\([a,b]\\)到\\((0,\infty)\\)的连续函数.
1. 证明任给\\(n\ge 2\\)，存在\\([a,b]\\)的唯一分割\\(x_0=a<x_1<\dots<x_n=b\\)使得
\\[\int_{x_k}^{x_{k+1}}f(t)\mathrm{d}t=\frac{1}{n}\int_a^bf(t)\mathrm{d}t,\quad \forall 0\le k\le n-1.\\]
2. 记\\(\displaystyle w_n=frac{1}{n}\sum_{k=1}^n f(x_k)\\)，求极限\\(\displaystyle\lim_{n\to\infty}w_n.\\)

## 2025春季学期期末考试

**第1题[15分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. 设\\(\sum u_n\\)收敛，且\\(-\|u_n\|\le v_n \le \|u_n\|\\)，则\\(\sum v_n\\)收敛.
2. 如果\\(u_n\\)是区间\\(I\\)上的\\(C^1\\)函数，且\\(S(x)=\sum u_n(x)\\)在\\(I\\)上依范数收敛，则和函数在\\(S\\)上是\\(C^1\\)的.
3. \\(f\in C^\infty(\mathbb{R})\\)对应的Maclaurin级数\\(\displaystyle\sum_{k\ge 0}\frac{f^{(k)}(0)}{k!}x^n\\)的收敛半径\\(R>0\\)，则\\(f\\)在\\(x=0\\)处实解析.

**第2题[15分]** 考虑函数\\(\displaystyle\Phi(x)=\int_0^{\sin^2 x}\arcsin\sqrt{t}\mathrm{d}t+\int_0^{\cos^2 x}\arccos\sqrt{t}\mathrm{d}t,x\in\mathbb{R}\\)，指出并证明函数\\(\Phi\\)的奇偶性和周期性. 计算\\(\Phi'(x)\\). 推出\\(\Phi(x)\\)的解析表达式.

**第3题[10分]** 设\\(\beta\in\mathbb{R}\\)为常数，根据\\(\beta\\)的取值，讨论以下通项的数项级数的敛散性.
\\[\forall n\ge 2 ,\quad u_n=\frac{n^\beta}{\sum_{2\le k\le n}(\ln k)^2}.\\]

**第4题[10分]** 求方程\\(\displaystyle\sum_{n\ge 0}(2n+1)^2x^n=0\\)所有的根.

**第5题[15分]** 令\\(\displaystyle J=\int_0^1\frac{1}{x^x}\mathrm{d}x\\)
1. 任给\\(k\ge 1\\)，证明积分\\(I_k=\int_0^1(x\ln x)^k\mathrm{d}x\\)收敛并求出\\(I_k\\).
2. 证明\\(J\\)收敛，且\\(J=\sum_{n\ge 1}n^{-n}\\).

**第6题[15分]** 设\\(f_0(x)=x\\)，任给\\(n\ge 1,x\in\mathbb{R}_+=[0,\infty)\\)，定义 \\(\displaystyle f_{n+1}(x)=\frac{x}{2+f_n(x)}\\)
1. 证明\\(f_0\ge f_2\ge f_1\\). 证明\\((f_n)\\)在\\(\mathbb{R}_+ \\)上逐点收敛，确定极限函数\\(f(x)\\).
2. 证明任给\\(n\in\mathbb{N},f_n(x)\\)是有理分式，即\\(f_n(x)=\frac{P_n}{Q_n}\\)，其中\\(P_n,Q_n\in\mathbb{R}[x]\\)，且\\(\deg(P_n)-\deg(Q_n)\\)取值为0或1.
3. 证明\\(f_n\\)在\\(\mathbb{R}_+\\)上不一致收敛.
4. 证明\\(f_n\\)在\\(\mathbb{R}_+\\)上内闭一致收敛.

**第7题[20分]** 设\\(\\)

**第8题[10分]**
