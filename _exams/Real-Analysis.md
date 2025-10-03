---
title: "实分析"
collection: exams
type: "Undergraduate course"
permalink: /exams/real_analysis
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
grade: 2.5
instructor: 袁海荣教授
---

<details markdown="1">
  <summary> 2024春季学期第一次小测</summary>

一、（10分）请叙述并证明Borel-Cantelli定理.

二、（10分）设 \\(X=\mathbb{R}\\) ，定义 \\(2^X\\) 上的集函数 $$\mu(A)=\begin{cases}1,&0\in A, \\ 0,&0\notin A.\end{cases}$$
证明 \\(\mu\\) 是一个测度.

三、（10分）设 \\(\mathcal{R}\\)是基本空间\\(X\\)上的\\(\sigma\\)-环，\\(\mu\\)是\\(\mathcal{R}\\)上非负的满足有限可加性和次可列可加性的集函数，且\\(\mu(\varnothing)=0\\). 证明\\\(\mu\\)是一个测度.

四、（10分）设集\\(E\\)上的实函数列\\(f_n\\)有极限\\(f\\)，证明：对任意实数\\(c\\)，成立
\\[E(f\le c)=\bigcap_{k=1}^\infty\liminf_{n\to\infty}E(f_n\le c+\frac{1}{k}). \\]

五、（15分）设\\(X=\mathbb{R}\\)，定义\\(2^X\\)上的集函数\\(\mu_* \\)使得\\(\mu_* (\varnothing)=0\\)，而当\\(A\neq\varnothing\\)时，\\(\mu_*(A)=1\\).
1. 证明：\\(\mu_*\\)是次可列可加的；
2. 写出：\\(\mu_*\\)可测集的Caratheodory条件；
3. 证明：\\(\mu_*\\)可测集构成的\\(\sigma\\)-代数是\\( \\{\varnothing,X\\} \\).

六、（15分）证明：任意可列集的有限子集的全体仍然是可列集.

七、（30分）设\\(X\\)是基本空间
1. \\(\mathcal{P}\subset 2^X,\mathcal{P}\neq\varnothing\\)，如果由\\(A,B\in\mathcal{P}\\)可知\\(A\cap B\in\mathcal{P}\\)，则称\\(\mathcal{P}\\)是一个\\(\pi\\)-系.
2. \\(\mathcal{L}\subset 2^X,\mathcal{L}\neq\varnothing\\)称为一个\\(\lambda\\)-系，若其具有如下性质：
   - \\(X\in\mathcal{L}\\);
   - 若\\(A,B\in \mathcal{L}\\)且\\(A\subset B\\)，则\\(B-A\in \mathcal{L}\\)；
   - 若\\(A_k\in\mathcal{L},k=1,2,\dots\\)，且\\(A_{k}\subset A_{K+1}\\)，则\\(\bigcup_{k=1}^\infty A_k\in\mathcal{L}\\).
3. 请按如下步骤证明如下\\(\underline{\pi-\lambda\text{定理}}\\)：设\\(\mathcal{P}\\)是\\(\pi\\)-系，\\(\mathcal{L}\\)是\\(\lambda\\)-系，且\\(\mathcal{P}\subset\mathcal{L}\\)，则\\(S(\mathcal{P})\subset \mathcal{L}\\). 这里\\(S(\mathcal{P})\\)是\\(\mathcal{P}\\)生成的\\(\sigma\\)-代数.
4. 定义\\(\mathcal{S}=\bigcap_{\mathcal{L}'\supset \mathcal{P}}\mathcal{L}'\\)，其中\\(\mathcal{L}'\\)是\\(\lambda\\)-系. 证明\\(\mathcal{S}\\)是包含\\(\mathcal{P}\\)的最小的\\(\lambda\\)-系.
5. 下面证明\\(\mathcal{S}\\)是\\(\pi\\)-系. 为此，作\\(\mathcal{A}=\\{C\subset X:A\cap C\in\mathcal{S}\\}\\). 证明：当\\(A\in\mathcal{P}\\)时，成立\\(\mathcal{P}\subset\mathcal{A}\\).
6. 请进一步证明：当\\(A\in \mathcal{S}\\)时，\\(\mathcal{A}\\)是\\(\lambda\\)-系.
7. 由此证明：\\(\mathcal{S}\subset\mathcal{A}\\)，并证明\\(\mathcal{S}\\)是\\(\pi\\)-系.
8. 证明：\\(\mathcal{S}\\)是\\(\sigma\\)-代数.
9. 证明：\\(S(\mathcal{P})\subset \mathcal{L}\\).
</details>

<details markdown="1">
  <summary> 2025春季学期第二次小测</summary>

一、（15分）证明：对任何给定的非负可测函数，都存在一列非负的单调递增的简单函数列处处收敛于它.

二、（15分）叙述并证明积分的全连续性.

三、（15分）叙述并证明Lebesgue控制收敛定理.

四、（15分）叙述并证明积分的可列可加性.

五、（15分）设\\((X,\mathcal{R},\mu)\\)是一个\\(\sigma\\)-有限测度空间，\\(E\in\mathcal{R}\\)，\\(f_n\\)是\\(E\\)上一列可测函数，且
\\[\lim_{m,n\to\infty}\int_E|f_m-f_n|^2\mathrm{d}\mu=0.\\]
证明：存在\\(E\\)上的可测函数\\(f\\)，使得
\\[\lim_{m,n\to\infty}\int_E|f_m-f|^2\mathrm{d}\mu=0.\\]

六、（15分）设\\(f\\)是区间\\([0,1]\\)上的连续函数，证明：
\\[\lim_{n\to\infty}\int_0^1\cdots\int_0^1f(\frac{x_1+\cdots+x_n}{n})\mathrm{d}x_1\cdots \mathrm{d}x_n=f(\frac{1}{2}).\\]

七、（10分）设\\(E\\)是测度空间\\((X,\mathcal{R},\mu)\\)上测度有限的集. 证明：函数\\(f\\)在\\(E\\)上可积的充分必要条件是\\(\sum_{n=1}^\infty n\mu(E_n)<\infty\\)，其中\\(E_n=E(n\le\|f\|<n+1).\\)
</details>

<details markdown="1">
  <summary> 2025春季学期期末考试</summary>

一、叙述并证明Helly选取原理.

二、叙述并证明Hahn分解定理.

三、证明\\([a,b]\\)上的有界变差函数全体与实数集等势.

四、设\\(f\\)是\\((-\infty,+\infty)\\)上满足\\(f(0)=0\\)的Lebesgue可积函数，证明\\(\displaystyle\sum_{n=-\infty}^{+\infty}f(n^2x)\\)必在\\((-\infty,+\infty)\\)上几乎处处（按Lebesgue测度）等于一个Lebesgue可积函数.

五、设\\((X,\mathcal{S},\mu),(Y,\mathcal{T},\nu)\\)是两个全有限测度空间，如果\\(E\\)是\\((X\times Y,\mathcal{S}\times\mathcal{T})\\)的可测子集，（证明：\\(E_x\\)和\\(E^y\\)是可测集？）证明：\\(\nu(E_x),\mu(E^y)\\)分别是\\((X,\mathcal{S},\mu),(Y,\mathcal{T},\nu)\\)上的可测函数，且
\\[\int_X\nu(E_x)\mathrm{d}\mu=\int_Y\mu(E^y)\mathrm{d}\nu.\\]

六、证明Лузин（鲁津）定理.
</details>
