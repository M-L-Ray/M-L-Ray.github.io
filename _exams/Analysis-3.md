---
title: "数学分析III(H)"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-3
venue: "ECNU"
date: 2025-01-23
location: "Shanghai, China"
---
主讲：叶东教授

## 2020秋季学期期末考试

**第1题[15分]** 判断下列陈述是否正确，并简述理由（判断3分，理由2分）
1. \\(\Omega\\)是\\(\mathbb{R^2}\\)中开集. 若\\(F=(P,Q)\in C^1(\Omega,\mathbb{R}^2)\\)满足在\\(\Omega\\)上\\(\partial_x Q-\partial_yP\equiv 0\\)，则\\(F\\)是\\(\Omega\\)上的梯度场.
2. 设\\(\mathbb{R}^3\\)中的向量场\\(F\\)满足\\(\mathrm{rot}(F)\\)在\\(Möbius\\)带\\(\mathcal{M}\\)上恒为零，则\\(F\\)在\\(\partial\mathcal{M}\\)上的第二型曲线积分为零.
3. 设\\(K=[0,1]^2,(f_n)\in C(K),(f_n)\\)递减且\\(f_n\to_{K}f\\). 则\\((f\in C(K)\\)当且仅当\\(f_n\rightrightarrows_K f\\).

**第1题[15分]** 判断下列陈述是否正确，并简述理由（每题判断3分，理由2分）  
1. \\(\Omega\\)是\\(\mathbb{R}^2\\)中开集. 若\\(F=(P,Q)\in C^1(\Omega,\mathbb{R}^2)\\)满足在\\(\Omega\\)上\\(\partial_x Q - \partial_y P \equiv 0\\)，则\\(F\\)是\\(\Omega\\)上的梯度场.  
2. 设\\(\mathbb{R}^3\\)中的向量场\\(F\\)满足\\(\mathrm{rot}(F)\\)在Möbius带\\(\mathcal{M}\\)上恒为零，则\\(F\\)在\\(\partial\mathcal{M}\\)上的第二型曲线积分为零.  
3. 设\\(K=[0,1]^2\\), \\((f_n) \subset C(K)\\), \\((f_n)\\)递减且\\(f_n \to f\\)于\\(K\\). 则\\(f \in C(K)\\)当且仅当\\(f_n \rightrightarrows f\\)于\\(K\\).  

**第2题[10分]** 考虑Descartes叶形线\\(F = \\{(x, y) \in \mathbb{R}^2 \mid x^3 + y^3 = 3xy\\}\\). 用\\(t = y/x\\)做参数，证明叶形线在第一象限围成的区域\\(D_F = \\{(x, y) \in \mathbb{R}^2 \mid x, y \geq 0, x^3 + y^3 \leq 3xy\\}\\)的面积为\\(\frac{3}{2}\\).  

**第3题[15分]** 令\\(D = \\{(x, y) \in \mathbb{R}^2 \mid 1 \leq xy \leq 2, 1 \leq x^2 - y^2 \leq 4\\}\\). 考虑\\(\Phi : \Omega_1 = (0, \infty)^2 \to \Omega_2 = (0, \infty) \times \mathbb{R}\\), \\(\Phi(x, y) = (xy, x^2 - y^2)\\). 证明\\(\Phi\\)是\\(\Omega_1\\)到\\(\Omega_2\\)的\\(C^\infty\\)微分同胚. 计算\\(\int_D \frac{xy(x^2 + y^2)}{x^2 - y^2}  dxdy\\).  

**第4题[15分]** 设\\(n \geq 2\\), \\(\alpha = (\alpha_i) \in (0, \infty)^n\\), \\(\Omega_\alpha = \\{(x_i) \in \mathbb{R}^n \mid x_i \geq 0, x_1^{\alpha_1} + \cdots + x_n^{\alpha_n} \leq 1\\}\\), \\(|\Omega_\alpha|\\)为\\(\Omega_\alpha\\)的体积.  
1. 令\\(n = 2\\), \\(\beta_i = 1/\alpha_i \ (i = 1, 2)\\), 证明\\(|\Omega_\alpha| = \frac{\Gamma(\beta_1 + 1)\Gamma(\beta_2 + 1)}{\Gamma(\beta_1 + \beta_2 + 1)}\\), 由此证明\\(\Gamma(\frac{1}{2}) = \sqrt{\pi}\\).  
2. 任给\\(n \geq 2\\), \\(\beta_i = 1/\alpha_i, \forall 1 \leq i \leq n\\), 证明\\(|\Omega_\alpha| = \frac{\prod_{1 \leq i \leq n}\Gamma(\beta_i + 1)}{\Gamma(\beta_1 + \cdots + \beta_n + 1)}\\).  
3. 由此推出\\(\mathbb{R}^n\\)中单位球的体积是\\(\frac{\pi^{n/2}}{\Gamma(\frac{n}{2} + 1)}\\), \\(\forall n \geq 1\\).  

**第5题[20分]** 令\\(\omega(x, y) = \frac{e^{-y}}{x^2 + y^2} \left[ (x \sin x - y \cos x)  dx + (x \cos x + y \sin x)  dy \right]\\). 任给\\(R > \epsilon > 0\\), \\(\Omega_{\epsilon,R} = (B_R \backslash B_\epsilon) \cap (\mathbb{R} \times (0, \infty))\\), \\(B_r\\)为以原点为圆心半径\\(r\\)的开球.  
1. 画图表示\\(\Omega_{\epsilon,R}\\), 标注\\(\partial \Omega_{\epsilon,R}\\)的方向. 证明对任意\\(R > \epsilon > 0\\), \\(\omega\\)沿\\(\partial \Omega_{\epsilon,R}\\)的积分为零.  
2. 设\\(r > 0\\), 证明在参数化\\((r \cos \theta, r \sin \theta)\\)下, \\(\omega |_{\Gamma_r} = e^{-r \sin \theta} \cos(r \cos \theta)  d\theta\\).  
3. 记\\(\Gamma_r = \partial B_r \cap (\mathbb{R} \times (0, \infty))\\), 证明\\(\lim_{r \to 0^+} \int_{\Gamma_r} \omega = \pi\\) 和 \\(\lim_{r \to \infty} \int_{\Gamma_r} \omega = 0\\). 由此推出\\(\int_0^\infty \frac{\sin x}{x}  dx = \frac{\pi}{2}\\).  

**第6题[15分]** 设\\(E = C^\infty(\mathbb{R}^n, \mathbb{R})\\), \\(E^* = L(E, \mathbb{R})\\), \\(\Lambda = \\{ \ell \in E^* \mid \ell(fg) = f(0)\ell(g) + g(0)\ell(f), \forall f, g \in E \\}\\).  
1. 设\\(\omega \equiv 1\\), 证明对任意\\(\ell \in \Lambda\\), \\(\ell(\omega) = 0\\).  
2. 给定\\(f \in E\\), 证明存在\\(\varphi \in C^\infty(\mathbb{R}^n, \mathbb{R}^n)\\)使得\\(f(x) = f(0) + \sum_{i=1}^n x^i \varphi^i(x), \forall x \in \mathbb{R}^n\\).  
3. 给定\\(\ell \in \Lambda\\), 推出存在\\(\alpha \in \mathbb{R}^n\\)使得\\(\ell(f) = \sum_{i=1}^n \alpha^i \frac{\partial f}{\partial x^i}(0)\\). \\(\dim(\Lambda)\\)是多少?  

**第7题[20分]** 设\\(f\\)在\\(\mathbb{R}_+^2 = (0,\infty) \times (0,\infty)\\)上连续且\\(f \geq 0\\), \\(\xi(x) = \int_0^\infty f(t,x)  dt\\), \\(\eta(t) = \int_0^\infty f(t,x)  dx\\)在\\((0, \infty)\\)上局部可积且在\\(\mathbb{R}_+\\)上广义可积.  
1. 设\\((g_n)\\)为\\(I = (0, \infty)\\)上的一列局部可积函数, 满足: \\(g_{n+1} \geq g_n\\), \\(g_n\\)在\\(I\\)上广义可积, \\(g_n \to g\\), \\(g\\)在\\(I\\)上局部可积且广义可积. 证明\\(\lim_{n \to \infty} \int_I g_n(s)  ds = \int_I g(s)  ds\\).  
2. 证明: 对任意\\(A > 0\\), \\(\int_0^A \xi(x)  dx = \int_0^\infty \left( \int_0^A f(t,x)  dx \right)  dt\\).  
3. 证明\\(\int_0^\infty \xi(x)  dx = \int_0^\infty \eta(t)  dt\\).  
4. 考虑\\(f(t,x) = \frac{1}{(1+t)(1+tx^2)}\\), 计算\\(\int_0^\infty \frac{\ln x}{x^2-1}  dx\\).
