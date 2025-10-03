---
title: "数学分析I"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-1
venue: "ECNU"
date: 2025-01-13
location: "Shanghai, China"
grade: 1.0
a: 大一上
instructor: 苗俊杰副教授，戴浩晖副教授，王丽萍教授，赵纯奕教授
---

<details markdown="1">
  <summary> 2023秋季学期第一次小测</summary>
  
**第1题[20分]** 判断下列陈述是否正确，并简述理由（判断2分，理由3分）
1. 给定数列\\(\\{a_n\\}\\)和实数\\(a\\)，若对任意\\(\varepsilon>0\\)，在\\(U(a,\varepsilon)\\)中总包含\\(\\{a_n\\}\\)中的无穷多项，则数列\\(\\{a_n\\}\\)以\\(a\\)为极限；
2. \\(f(x)=\max\\{\|x\|,e^x\\},x\in\mathbb{R}\\)是一个初等函数；
3. 给定数列\\(\\{a_n\\}\\)，若对任意\\(\varepsilon>0\\)，存在\\(N>0\\)使得对\\(n>N\\)都有\\(\|a_n-a_{2n}\|<\varepsilon\\)，则数列\\(\\{a_n\\}\\)收敛；
4. 存在一个数列\\(\\{a_n\\}\\)，对任意\\(a\in[0,1]\\)，都存在一个子列\\(\\{a_{n_{k}}\\}\\)使得\\(\lim\limits_{k\to +\infty}a_{n_{k}}=a.\\)

**第2题[10分]** 写出下确界的定义，并对给定的非空有界集合\\(A\\)与\\(B\\)，证明\\(\inf(A\cup B)=\min\\{\inf A,\inf B\\}.\\)

**第3题[10分]** 给定数列\\(\\{a_n\\}\\)和实数\\(a\\)，若对任意\\(k\in\mathbb{N}_ +\\)，存在\\(N>0\\)，使得对任意\\(n>N\\)，都有\\(\|a_n-a\|<\dfrac{1}{10^k}\\). 证明\\(\lim\limits_{n\to+\infty}a_n=a.\\) 

**第4题[10分]** 写出数列极限的\\(\varepsilon-N\\)定义，并用其证明\\(\lim\limits_{n\to+\infty}\dfrac{6n^2+7}{4n^2+4n+1}=\dfrac{3}{2}.\\)

**第5题[10分]** 证明数集\\(\\{x\in\mathbb{Q}:x^2\le 2\\}\\)没有最大元.

**第6题[10分]** 写出非正常极限\\(\lim\limits_{n\to+\infty}a_n=\infty\\)的定义，并用其证明\\(\lim\limits_{n\to+\infty} (-n)^n=\infty\\).

**第7题[10分]** 设\\[a_n=\sqrt{1+\sqrt{2+\cdots+\sqrt{n}}}\\]证明\\(\\{a_n\\}\\)收敛.

**第8题[10分]** 设\\(x_1=a>0,x_{n+1}=10\sqrt{x_n},n=1,2,\cdots\\)，求数列\\(\\{x_n\\}\\)的极限.

**第9题[10分]** 叙述数列收敛的柯西准则，并用其证明\\(\\{\sin n\\}\\)不收敛.

</details>
<details markdown="1">
  <summary> 2023秋季学期第二次小测</summary>
  
**第1题[20分]** 判断下列陈述是否正确，并简述理由（判断2分，理由3分）
1. 若\\(\lim\limits_{x\to+\infty}f(x)\\)和\\(\lim\limits_{x\to+\infty}f(x)g(x)\\)都存在，则\\(g(x)\\)在\\(+\infty\\)存在极限；
2. 若函数\\(f\\)、\\(f-g\\)在\\(x_0\\)处都连续，则\\(g\\)在\\(x_0\\)处也连续；
3. 区间\\((a,b)\\)上的连续函数\\(f(x)\\)在区间\\((a,b)\\)上必定一致连续；
4. 设\\(f(x),g(x)\\)均为\\(x\to x_0\\)时的无穷小量且\\(f(x)=O(g(x)),x\to x_0\\)，若\\(f(x)\\)不是\\(g(x)\\)的同阶量，那么\\(f(x)\\)必定是\\(g(x)\\)的高阶无穷小量.

**第2题[12分]** 写出极限\\(\lim\limits_{x\to x_0^+}f(x)=A\\)的\\(\varepsilon-\delta\\)定义，并用其证明\\(\lim\limits_{x\to 1^+}\dfrac{x^3+1}{x}=2.\\)

**第3题[12分]** 叙述极限\\(\lim\limits_{x\to x_0^-}f(x)=A\\)的柯西收敛准则并用其证明\\(\lim\limits_{x\to 0^-}\cos\frac{1}{x^2}\\)不存在.

**第4题[12分]** 设函数\\( f\\)在\\(x_0\\)处连续，证明\\(\forall \alpha>f(x_0),\exists\ \delta>0\\)，当\\(\|x-x_0\|<\delta\\)时，\\(f(x)<a\\).

**第5题[12分]** 给出函数\\(f\\)在区间\\(I\\)上不一致收敛的充要条件，并用其验证\\(y=\sin x^2\\)在\\([0,+\infty)\\)上不一致收敛.

**第6题[12分]** 证明：
1. \\(\sqrt{x+\sqrt{x+\sqrt{x}}}\sim \sqrt[8]{x},x\to 0,\\)
2. \\(\sqrt{x+\sqrt{x+\sqrt{x}}}\sim \sqrt{x},x\to +\infty.\\)
  
**第7题[10分]** 证明\\(\lim\limits_{x\to -\infty}f(x)=\infty\\)的充要条件是：对任意单调减且趋于\\(-\infty\\)的数列\\(\\{x_n\\}\\)都有\\(\lim\limits_{n\to \infty}f(x_n)=\infty\\).

**第8题[10分]** \\(f(x)\\)定义在\\([a,b]\\)上，对每一点\\(x_0\in[a,b]\\)满足：\\(\forall \varepsilon,\ \exists\ \delta>0\\)，当\\(x\in(x_0-\delta,x_0+\delta)\cap[a,b] \\)时\\(f(x)>f(x_0)-\varepsilon\\). 证明：\\(f(x)\\)在\\([a,b]\\)上能取得最小值.

</details>

<details markdown="1">
  <summary>2024秋季学期第二次小测</summary>

**第1题[30分]** 判断下列陈述是否正确，并简述理由
1. 设 \\( A \in \mathbb{R} \\), 且 \\( \forall n \in \mathbb{N} \\), 存在 \\( \delta > 0 \\), 当 \\( 0 < \|x - x_0\| < \delta \\) 时成立 \\( \|f(x) - A\| < \dfrac{1}{n} \\), 则 \\( \lim\limits_{x \to x_0} f(x) = A \\).  
2. 若 \\( f(x) \\) 在 \\( x_0 \\) 的某空心邻域内有定义且 \\( \lim\limits_{x \to x_0} \|f(x)\| \\) 存在，则 \\( \lim\limits_{x \to x_0} f(x) \\) 也存在.  
3. 若存在正数 \\( \varepsilon_0 \\) 和两个数列 \\( \\{x_n\\} \\), \\( \\{y_n\\} \\) 满足 \\( x_n \to x_0 \\), \\( y_n \to x_0 \\), 且 \\( \forall n \in \mathbb{N}_ + \\), \\( \|f(x_n) - f(y_n)\| \geq \varepsilon_0 \\), 则 \\( \lim\limits_{x \to x_0} f(x) \\) 不存在.  
4. 若 \\( f(x) \\) 在点 \\( x_0 \\) 的某空心邻域内单调有界，则 \\( f(x) \\) 在点 \\( x_0 \\) 处的极限存在.  
5. 设 \\( f(x) \\) 定义在 \\( (1,+\infty) \\) 上，且当 \\( x \to +\infty \\) 时 \\( f(x) \\) 不是无穷大量，则存在数列 \\( \\{x_n\\} \subset (1,+\infty) \\), 使得 \\( x_n \to +\infty \\) 且数列 \\( \\{f(x_n)\\} \\) 有界.  

**第2题[30分]** 计算题 
1. 求极限 \\( \lim\limits_{x \to +\infty} (\sqrt{x+1} - \sqrt{x}) \cos x \\).  
2. 求极限 \\( \lim\limits_{x \to 0} \dfrac{\tan x - \sin x}{x^2 \sin 2x} \\).  
3. 求极限 \\( \lim\limits_{x \to 0} \left( \dfrac{1+2x}{1-x} \right)^{\cot x} \\).  
4. 求极限 \\( \lim\limits_{x \to +\infty} \left( \dfrac{[x]}{x} + \left[ \dfrac{1}{x} \right] \right) \\), 其中 \\( [ \cdot ] \\) 表示向下取整.  
5. 求函数 \\( f(x) = \dfrac{x^3 + 2}{x^2(x-1)} \\) 的渐近线.  

**第3题[10分]** 判断函数 \\( f(x) = \dfrac{\sin x}{x^2} + \dfrac{x+2}{(x^2-4)(x+1)} \\) 的间断点，并指明其类型.  

**第4题[10分]** 设函数 \\( f(x) \\) 在 \\( [a,b] \\) 上有定义，\\( \forall x \in (a,b) \\), 且 \\( \forall x,y \in [a,b] \\), \\( x \neq y \\) 时有 \\( \|f(x) - f(y)\| < \|x - y\| \\). 证明：存在唯一的点 \\( \xi \in [a,b] \\), 使得 \\( f(\xi) = \xi \\).  

**第5题[10分]** 设函数 \\( f(x) \\) 定义在 \\( \mathbb{R} \\) 上，且在 \\( x = 0 \\) 处连续. 若存在 \\( a \in (0,1) \\) 满足 \\( \forall x \in \mathbb{R} \\) 有 \\( f(ax) = f(x) \\), 证明：\\( f(x) = f(0) \\), \\( \forall x \in \mathbb{R} \\).  

**第6题[10分]** 设 \\( f(x) \\) 在 \\( U^o(0,1) \\) 上有定义，满足 \\( \lim\limits_{x \to 0} f(x) = 0 \\) 且 \\( f(x) - f\left(\dfrac{x}{2}\right) = o(x) \\) (\\( x \to 0 \\)). 证明：\\( f(x) = o(x) \\) (\\( x \to 0 \\)).  

</details>

<details markdown="1">
  <summary>2024秋季学期期末考试</summary>

**第1题[16分]** 判断下列命题是否正确并给出理由（每题4分）  
1. 若 \\(\forall n \in \mathbb{N}^+\\)，\\(\exists \delta > 0\\)，\\(\forall x \in (x_0 - \delta, x_0) \cup (x_0, x_0 + \delta)\\)，\\(\|f(x) - A\| < \dfrac{1}{\sqrt{n}}\\)，则 \\(\lim\limits_{x \to x_0} f(x) = A\\).  
2. 任意数列必有收敛子列.  
3. 若 \\(f(x)\\) 在 \\((a, b]\\) 上一致连续，则 \\(\lim\limits_{x \to a^+} f(x)\\) 存在.  
4. 设 \\(D(x)\\) 为 Dirichlet 函数，则存在函数 \\(F(x)\\)，使得 \\(F'(x) = D(x)\\).  

**第2题[20分]** 计算下列极限或导数
1. 求 \\(\lim\limits_{n \to \infty} \left( 1 + \dfrac{1}{2n+1} \right)^n\\).  
2. 求 \\(\lim\limits_{x \to 0} \dfrac{(1+x)^{\frac{1}{3}}-1}{\ln(1+x)}\\).  
3. 求 \\(\lim\limits_{x \to 0} \left( \dfrac{1}{\sin^2 x} - \dfrac{1}{x^2} \right)\\).  
4. 计算 \\(f'(x)\\)，其中 \\(\displaystyle f(x) = \begin{cases} x^2 \cos \frac{1}{x} & x \neq 0 \\\ 0 & x = 0 \end{cases}\\).  

**第3题[6分]**  证明： \\(\tan x + \sin x > 2x\\)， \\(\forall x \in \left(0, \dfrac{\pi}{2}\right)\\).  

**第4题[8分]**  研究 \\(\displaystyle f(x) = \frac{(\ln x)^2}{x}\\) 有哪些极值？若是最值也请指出.  

**第5题[8分]**  设 \\(\displaystyle a_n = \sin 1 + \frac{\sin 2}{2^2} + \cdots + \frac{\sin n}{n^2}\\)，证明： \\(\\{a_n\\}\\) 收敛.  

**第6题[8分]**  设 \\(f\\) 是在开区间 \\(I\\) 上的凸函数， \\(g\\) 是在开区间 \\(J\\) 上的严格单增凸函数， \\(f(I) \subset J\\)，若 \\(g \circ f\\) 在 \\(I\\) 上存在最大值，证明： \\(f\\) 是常值函数.  
**第7题[8分]**  设 \\(f(x)\\) 在 \\([a, b]\\) 上一阶连续可导，在 \\((a, b)\\) 上二阶可导且存在一个极值点，证明：存在 \\(\xi \in (a, b)\\)，使得 \\(\displaystyle \|f(b) - f(a)\| \leq \frac{(b-a)^2}{2} \|f''(\xi)\|\\).  

**第8题[8分]**  设 \\(f(x)\\) 是定义在 \\((-\infty, +\infty)\\) 上的连续函数，且 \\(\displaystyle \lim\limits_{x \to \infty} f(x) = A\\)，证明： \\(f(x)\\) 必在 \\((-\infty, +\infty)\\) 上存在最值.  

**第9题[8分]**  设 \\(f(x)\\) 在 \\([a, b]\\) 上连续，在 \\((a, b)\\) 上可导，且 \\(f(x)\\) 不是线性函数，证明：存在 \\(\xi_1, \xi_2 \in (a, b)\\)，使得 \\(\displaystyle f'(\xi_1) > \frac{f(b)-f(a)}{b-a}\\), \\(\displaystyle f'(\xi_2) < \frac{f(b)-f(a)}{b-a}\\).  

**第10题[10分]**  用有限覆盖定理证明聚点定理.  

</details>
