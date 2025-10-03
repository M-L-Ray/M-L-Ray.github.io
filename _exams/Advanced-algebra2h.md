---
title: "高等代数II(H)"
collection: exams
type: "Undergraduate course"
permalink: /exams/Advanced-algebra2h
venue: "ECNU"
date: 2024-06-24
location: "Shanghai, China"
grade: 1.5
a: 大一下
instructor: 罗栗教授
---

<details markdown="1">
  <summary>2024春季学期期末考试</summary>

**第1题[20分]** 判断下列命题正误，并说明理由：  
(1) 两个正交矩阵之和还是正交矩阵；  
(2) 两个矩阵的特征值及其代数重数完全相同，则它们相似；  
(3) 两个实对称矩阵相似，则它们相合；  
(4) 复矩阵 \\( A,B \\) 满足 \\( A^2 \sim B^2 \\)，则 \\( A \sim B \\) . 

**第2题[10分]** 求三阶实对称矩阵 \\( A \\)，其特征值为 \\( 6,3,3 \\)，其中特征值 \\(6\\) 对应的一个特征向量为 \\( (1,1,1)^T \\) . 

**第3题[15分]** 定义 \\( M_2(\mathbb{R}) \times M_2(\mathbb{R}) \to \mathbb{R} \\) 的函数：\\( f(A,B) = |A+B| - |A| - |B| \\) .   
(1) 证明 \\( f \\) 是对称双线性函数；  
(2) 求 \\( f \\) 在 \\( E_{11}, E_{12}, E_{21}, E_{22} \\) 下的度量矩阵，并求 \\( f \\) 的符号差 . 

**第4题[10分]** 已知 \\( A = \begin{pmatrix} 0 & 2024 & 6 \\\ & 0 & 24 \\\ & & 0 \end{pmatrix} \\)，求证方程 \\( X^2 = A \\) 无解（\\( X \in M_3(\mathbb{C}) \\)） . 

**第5题[15分]** 求矩阵 \\( A = \begin{pmatrix} -4 & 3 & 0 & 0 \\\ -3 & 2 & 0 & 0 \\\ 5 & 1 & 1 & -2 \\\ 2 & 0 & 2 & -3 \end{pmatrix} \\) 的初等因子，不变因子以及 Jordan 标准型 . 

**第6题[10分]** 已知线性空间 \\( V \\) 上的线性函数 \\( f, f_1, f_2, \cdots, f_k \in \text{Hom}(V,\mathbb{K}) \\) 满足当 \\( f_1(\alpha) = f_2(\alpha) = \cdots = f_k(\alpha) \\) 时都有 \\( f(\alpha) = 0 \\)，求证 \\( f \\) 是 \\( f_1, f_2, \cdots, f_k \\) 的线性组合 . 

**第7题[10分]** 已知矩阵 \\( A \in M_n(\mathbb{C}) \\) 有 \\( n \\) 个不同的特征值 \\( \lambda_1, \lambda_2, \cdots, \lambda_n \\)，定义变换 \\( \text{ab}_A(B) = A B - B A \\) .   
(1) 求证 \\( \text{ab}_A \\) 是 \\( M_n(\mathbb{C}) \\) 上的线性变换；  
(2) 求线性变换 \\( \text{ab}_A \\) 的 \\( n^2 \\) 个特征值 . 

**第8题[10分]** 定义对角线全为 1 的 \\( m \\) 阶复上三角矩阵全体为 \\( N_m^+ \\)，对角线全为 1 的 \\( n \\) 阶复下三角矩阵全体为 \\( N_n^- \\)，定义 \\( M_{m \times n}(\mathbb{C}) \\) 上的关系 \\( A \sim B \\)：\\( \exists P \in N_m^+, Q \in N_n^- \\) 使得 \\( A = P B Q \\) .   
(1) 求证该关系是 \\( M_{m \times n}(\mathbb{C}) \\) 上的等价关系；  
(2) \\( \Delta_i \\) 定义为 \\( A \\) 的 \\( i \\) 阶顺序主子式，求证：\\( \Delta_1, \cdots, \Delta_{\min\\{m,n\\}} \\) 是上述等价关系的不变量 . 
</details>

<details markdown="1">
  <summary>2025春季学期期中考试</summary>

本次考试的数学目标是给出代数基本定理的一种证明。（Harm Derksen,2023）

**定理1.** 令\\( f(x)\in\mathbb{C}[x] \\)且\\(\deg f>0\\)，则存在\\(\alpha\in\mathbb{C}\\)使得\\(f(\alpha)=0\\)。

### -准备-
我们不妨设\\(f(x)=\displaystyle\sum_{i=0}^na_ix^i\\)，其中\\(a_n=1,n\ge 1\\)。令\\(\overline{f}(x)=\displaystyle\sum_{i=0}^n\overline{a_i}x^i\\)，其中\\(\overline{a_i}\\)是\\(a_i\\)的共轭复数。

**【题一：(20')】** 令\\(g(x)=f(x)\cdot\overline{f}(x)\\)，证明：
1. \\(g(x)\in\mathbb{R}[x]\\)。
2. \\(f\\)有复根当且仅当\\(g\\)有复根。

由题一，我们下面可以用\\(g\\)替换\\(f\\)
，总是假定\\(f(x)\in\mathbb{R}[x]\\)。考虑实\\(n\\)级矩阵\\(A=(c_{ij})\\)满足\\(c_{in}=-a_{i-1}\\)，对任意\\(1\le i\le n\\)，\\(c_{i,i-1}=1\\)，对任意\\(2\le i\le n\\)，其余地方为\\(0\\)。容易验证\\(A\\)的特征多项式为\\(f(x)\\)。

**【题二：(15')】** 令\\(f(x)=x^2-1\\)。写出如上构造的矩阵\\(A\\)。

于是，代数学基本定理等价于如下定理。所以我们只专注于定理2的证明。

**定理2.** 任何\\(n\\)级**实**方阵\\(A\\)（线性映射）都存在（复）特征向量。

令\\(n\\)是一个正整数，由唯一分解，我们可以写\\(n=2^{r_2}\cdot 3^{r_3}\cdots\\)。定义\\(v_2(n):=r_2\\)。

**【题三：(10')】** 用数分证明“初始”情形：当\\(v_2(n)=0\\)时，定理1（所以定理2）成立。

### -进阶-

令\\(M\\)是所有\\(n\\)级复方阵构成的线性空间。则\\(A\\)诱导了两个线性映射\\(L:M\to M\\)通过\\(X\mapsto A^TX\\)以及\\(R:M\to M\\)通过\\(X\mapsto XA\\)。

令\\(S\\)是所有\\(n\\)级**复对称**方阵构成的线性子空间。我们又有两个自然生成的线性映射\\(\alpha:S\to S\\)通过\\(X\mapsto L(X)+R(X)=A^TX+XA\\)，以及\\(\beta:S\to S\\)通过\\(X\mapsto L\circ R(X)=R\circ L(X)=A^TXA\\)。

**【题四：(20')】** 令\\(v_2(n)=r\\)。证明\\(\dim S=\frac{n(n+1)}{2}\\)以及\\(v_2(\dim S)<r\\)。

我们对\\(v_2(n)\\)归纳，初始情形已由题三给出，现在可假设**定理2对于\\(v_2(n)<r\\)情形成立**。

我们考虑\\(v_2(n)=r\\)情形。由题四，\\(\alpha,\beta\\)都有（复）特征向量。

但这不够，我们需要证明\\(\alpha,\beta\\)有公共特征向量：

**引理3.** 存在\\(0\neq X\in S,\lambda,\mu\in\mathbb{C}\\)使得\\(\alpha(X)=\lambda X,\beta(X)=\mu X\\)。

令\\(S_\lambda\\)是\\(\alpha\\)的\\(\lambda\\)-特征子空间，令\\(I_\lambda=\mathrm{Im}(\lambda\cdot\mathrm{id}-\alpha)\\)。显然\\(\alpha(S_\lambda)\subseteq S_{\lambda}\\)以及\\(\alpha(I_\lambda)\subseteq I_\lambda\\)。

**【题五：(20')】** 严格证明：
1. \\(\beta(S_\lambda)\subset S_\lambda,\beta(I_\lambda)\subseteq(I\lambda)\\)。
2. \\(\min\\{v_2(\dim S_\lambda),v_2(\dim I_\lambda)\\}\le v_2(\dim S)\\)。
3. 如果\\(v_2(\dim S_\lambda)\le v_2(\dim S)\\)，那么\\(a\|_ {S_\lambda},\beta\|_ {I_\lambda}\\)有公共特征向量。
4. 如果\\(v_2(\dim S_\lambda)> v_2(\dim S)\\)，那么\\(a\|_ {I_\lambda},\beta\|_ {I_\lambda}\\)有公共特征向量。（注意，这里特征值可能会变）

如题五，我们完成了引理3的证明。

### -终章-

令\\(t\\)是二次方程\\(x^2-\lambda x+\mu =0\\)的一个复根。考虑如下映射
\\[\varphi:=(t\cdot\mathrm{id}-L)\circ (t\cdot \mathrm{id}-R):M\to M\\]

**【题六：(15')】** 证明：
1. \\(\varphi(X)=0\\)，其中\\(X\\)由引理3所得。
2. \\(t\\)是\\(L\\)或者\\(R\\)的特征值。
3. \\(t\\)是\\(A\\)的特征值。（我们完成了代数基本定理的证明！）

**【附加：(10')】** 详细阐述作者是如何证明\\(f(x)=x^2-1\\)有根的？（需要写出\\(L\\)和\\(R\\)的特征多项式）
</details>
