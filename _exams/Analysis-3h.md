---
title: "数学分析III(H)"
collection: exams
type: "专业必修课程"
permalink: /exams/analysis-3h
venue: "ECNU"
date: 2025-01-23
location: "Shanghai, China"
grade: 2.0
a: 大二上
instructor: 叶东教授
---

<div class="exam-toc">
  <h2>考试目录</h2>
  <ul>
    <li><a href="#2020-fall-final">2020秋季学期期末考试</a></li>
    <li><a href="#2022-fall-final">2022秋季学期期末考试</a></li>
    <li><a href="#2023-fall-final">2023秋季学期期末考试</a></li>
    <li><a href="#2024-fall-final">2024秋季学期期末考试</a></li>
  </ul>
</div>

<style>
.exam-toc {
  background: #f8f9fa;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 2rem 0;
  border-left: 4px solid #4285f4;
}

.exam-toc h2 {
  margin-top: 0;
  color: #2c3e50;
}

.exam-toc ul {
  list-style: none;
  padding-left: 0;
}

.exam-toc li {
  margin: 0.8rem 0;
  padding: 0.5rem;
  border-radius: 4px;
  transition: background 0.3s;
}

.exam-toc li:hover {
  background: #e3f2fd;
}

.exam-toc a {
  text-decoration: none;
  color: #4285f4;
  font-weight: 500;
  display: block;
}

.exam-header {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 1.5rem 0;
}

.exam-header h3 {
  margin: 0;
  font-size: 1.4rem;
}

.exam-meta {
  opacity: 0.9;
  font-size: 0.9rem;
  margin-top: 0.5rem;
}

details {
  background: white;
  border: 1px solid #e1e4e8;
  border-radius: 8px;
  margin: 1.5rem 0;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: box-shadow 0.3s;
}

details:hover {
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

summary {
  background: #f6f8fa;
  padding: 1.2rem 1.5rem;
  cursor: pointer;
  font-weight: 600;
  color: #2c3e50;
  border-radius: 8px 8px 0 0;
  font-size: 1.1rem;
}

details[open] summary {
  border-bottom: 1px solid #e1e4e8;
}

.exam-content {
  padding: 1.5rem;
}

.question {
  margin: 1.5rem 0;
  padding: 1rem;
  background: #fafbfc;
  border-radius: 6px;
  border-left: 3px solid #4285f4;
}

.question-title {
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.8rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.points {
  background: #4285f4;
  color: white;
  padding: 0.2rem 0.6rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 500;
}

.math-content {
  line-height: 1.6;
  font-size: 1rem;
}

.math-content p {
  margin: 0.8rem 0;
}

.proof {
  background: #fff3e0;
  border: 1px solid #ffb74d;
  border-radius: 6px;
  padding: 1rem;
  margin: 1rem 0;
}

.proof-title {
  font-weight: 600;
  color: #e65100;
  margin-bottom: 0.5rem;
}

@media (max-width: 768px) {
  .exam-content {
    padding: 1rem;
  }
  
  summary {
    padding: 1rem;
  }
  
  .question {
    padding: 0.8rem;
  }
}
</style>

<div id="2020-fall-final" class="exam-header">
  <h3>2020秋季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（每题判断3分，理由2分）</p>
        <p>1. \(\Omega\)是\(\mathbb{R}^2\)中开集. 若\(F=(P,Q)\in C^1(\Omega,\mathbb{R}^2)\)满足在\(\Omega\)上\(\partial_x Q - \partial_y P \equiv 0\)，则\(F\)是\(\Omega\)上的梯度场.</p>
        <p>2. 设\(\mathbb{R}^3\)中的向量场\(F\)满足\(\mathrm{rot}(F)\)在Möbius带\(\mathcal{M}\)上恒为零，则\(F\)在\(\partial\mathcal{M}\)上的第二型曲线积分为零.</p>
        <p>3. 设\(K=[0,1]^2\), \((f_n) \in C(K)\), \((f_n)\)递减且\(f_n \to_K f\). 则\(f \in C(K)\)当且仅当\(f_n \rightrightarrows_K f\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>考虑Descartes叶形线\(F = \{(x, y) \in \mathbb{R}^2 \mid x^3 + y^3 = 3xy\}\). 用\(t = y/x\)做参数，证明叶形线在第一象限围成的区域\(D_F = \{(x, y) \in \mathbb{R}^2 \mid x, y \geq 0, x^3 + y^3 \leq 3xy\}\)的面积为\(\frac{3}{2}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>令\(D = \{(x, y) \in \mathbb{R}^2 \mid 1 \leq xy \leq 2, 1 \leq x^2 - y^2 \leq 4\}\). 考虑\(\Phi : \Omega_1 = (0, \infty)^2 \to \Omega_2 = (0, \infty) \times \mathbb{R}\), \(\Phi(x, y) = (xy, x^2 - y^2)\). 证明\(\Phi\)是\(\Omega_1\)到\(\Omega_2\)的\(C^\infty\)微分同胚. 计算\(\displaystyle\int_D \frac{xy(x^2 + y^2)}{x^2 - y^2}  \mathrm{d}x\mathrm{d}y\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设\(n \geq 2\), \(\alpha = (\alpha_i) \in (0, \infty)^n\), \(\Omega_\alpha = \{(x_i) \in \mathbb{R}^n \mid x_i \geq 0, x_1^{\alpha_1} + \cdots + x_n^{\alpha_n} \leq 1\}\), \(|\Omega_\alpha|\)为\(\Omega_\alpha\)的体积.</p>
        <p>1. 令\(n = 2\), \(\beta_i = 1/\alpha_i \ (i = 1, 2)\), 证明\(\|\Omega_\alpha\| = \dfrac{\Gamma(\beta_1 + 1)\Gamma(\beta_2 + 1)}{\Gamma(\beta_1 + \beta_2 + 1)}\), 由此证明\(\Gamma(\dfrac{1}{2}) = \sqrt{\pi}\).</p>
        <p>2. 任给\(n \geq 2\), \(\beta_i = 1/\alpha_i, \forall 1 \leq i \leq n\), 证明\(\|\Omega_\alpha\| = \dfrac{\prod_{1 \leq i \leq n}\Gamma(\beta_i + 1)}{\Gamma(\beta_1 + \cdots + \beta_n + 1)}\).</p>
        <p>3. 由此推出\(\mathbb{R}^n\)中单位球的体积是\(\dfrac{\pi^{n/2}}{\Gamma(\frac{n}{2} + 1)}\), \(\forall n \geq 1\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令\(\displaystyle\omega(x, y) = \frac{e^{-y}}{x^2 + y^2} \left[ (x \sin x - y \cos x)  \mathrm{d}x + (x \cos x + y \sin x)  \mathrm{d}y \right]\). 任给\(R > \epsilon > 0\)，记 \(\Omega_{\epsilon,R} = (B_R \backslash \overline{B_\epsilon}) \cap (\mathbb{R} \times (0, \infty))\), \(B_r\)为以原点为圆心半径\(r\)的开球.</p>
        <p>1. 画图表示\(\Omega_{\epsilon,R}\), 标注\(\partial \Omega_{\epsilon,R}\)的方向. 证明对任意\(R > \epsilon > 0\), \(\omega\)沿\(\partial \Omega_{\epsilon,R}\)的积分为零.</p>
        <p>2. 设\(r > 0\), 证明在参数化\((r \cos \theta, r \sin \theta)\)下, \(\omega \|_{\Gamma_r} = e^{-r \sin \theta} \cos(r \cos \theta)  \mathrm{d}\theta\).</p>
        <p>3. 记\(\Gamma_r = \partial B_r \cap (\mathbb{R} \times (0, \infty))\), 证明\(\left\|\displaystyle\lim_{r \to 0^+} \int_{\Gamma_r} \omega \right\|= \pi\) 和 \(\displaystyle\lim_{r \to \infty} \int_{\Gamma_r} \omega = 0\). 由此推出\(\displaystyle\int_0^\infty \frac{\sin x}{x}  \mathrm{d}x = \frac{\pi}{2}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设\(E = C^\infty(\mathbb{R}^n, \mathbb{R})\)和它的对偶空间\(E^* = L(E, \mathbb{R})\)，考虑\(E^* \)的线性子空间
        \[\Lambda = \{ \ell \in E^* \mid \ell(fg) = f(0)\ell(g) + g(0)\ell(f), \forall f, g \in E \}.\]</p>
        <p>1. 设\(\omega \equiv 1\), 证明对任意\(\ell \in \Lambda\), \(\ell(\omega) = 0\).</p>
        <p>2. 给定\(f \in E\), 证明存在\(\varphi \in C^\infty(\mathbb{R}^n, \mathbb{R}^n)\)使得\(\displaystyle f(x) = f(0) + \sum_{i=1}^n x^i \varphi^i(x), \forall x \in \mathbb{R}^n\).</p>
        <p>3. 给定\(\ell \in \Lambda\), 推出存在\(\alpha \in \mathbb{R}^n\)使得\(\displaystyle\ell(f) = \sum_{i=1}^n \alpha^i \frac{\partial f}{\partial x^i}(0)\). \(\dim(\Lambda)\)是多少?</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设\(f\)在\(\mathbb{R}_ +^2 = (0,\infty) \times (0,\infty)\)上连续且\(f \geq 0\), \(\displaystyle\xi(x) = \int_0^\infty f(t,x)  \mathrm{d}t\), \(\displaystyle\eta(t) = \int_0^\infty f(t,x)  \mathrm{d}x\)在\((0, \infty)\)上局部可积且在\(\mathbb{R}_ +\)上广义可积.</p>
        <p>1. 设\((g_n)\)为\(I = (0, \infty)\)上的一列局部可积函数, 满足: \(g_{n+1} \geq g_n\), \(g_n\)在\(I\)上广义可积, \(g_n \to g\), \(g\)在\(I\)上局部可积且广义可积. 证明\(\displaystyle\lim_{n \to \infty} \int_I g_n(s)  \mathrm{d}s = \int_I g(s)  \mathrm{d}s\).</p>
        <p>2. 证明: 对任意\(A > 0\), \(\displaystyle\int_0^A \xi(x)  \mathrm{d}x = \int_0^\infty \left( \int_0^A f(t,x)  \mathrm{d}x \right)  \mathrm{d}t\).</p>
        <p>3. 证明\(\displaystyle\int_0^\infty \xi(x)  \mathrm{d}x = \int_0^\infty \eta(t)  \mathrm{d}t\).</p>
        <p>4. 考虑\(\displaystyle f(t,x) = \frac{1}{(1+t)(1+tx^2)}\), 计算\(\displaystyle\int_0^\infty \frac{\ln x}{x^2-1}  \mathrm{d}x\).</p>
      </div>
    </div>
  </div>
</details>

<div id="2022-fall-final" class="exam-header">
  <h3>2022秋季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（每题判断3分，理由2分）</p>
        <p>1. 设\(f_t(\cdot) (t\in\Lambda)\)是\(\mathbb{R}_ +\)上一族连续且广义可积的函数，若存在连续函数\(g\)使得\(\|f_t(x)\|\le g(x)\)对任意\(t\in\Lambda,x\in\mathbb{R}_ +\)成立，那么广义积分
        \[\int_0^\infty f_t(x)\mathrm{d}x\text{对于}t\in\Lambda\text{一致收敛.}\]</p>
        <p>2. 设\((f_k)\)是\(\Sigma=[0,1]^n\)上的\(C^1\)函数列，满足\(f_k\rightrightarrows_\Sigma f\)，则\(f\in C(\Sigma)\)，且\(f\in C^1(\Sigma)\)当且仅当\(\mathrm{d}f_k\)在\(\Sigma\)上也是一致收敛的.</p>
        <p>3. 设\(f\)是开集\(\Omega\subset\mathbb{R}^n\)上的\(C^1\)函数，满足\(\|\mathrm{d}f(x)\|\le\ell,\forall x\in \Omega\)，则\(f\)是\(\Omega\)上的\(\ell\)-Lipschitz函数.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令\(E=M_n(\mathbb{R})\)为\(n\)阶实方阵空间，记\(U=GL_n(\mathbb{R})\)是实可逆阵集合，\(I_n\)为单位阵.</p>
        <p>1. 证明\(U\)是\(E\)中开集.</p>
        <p>2. 考虑\(E^2\)上映射\(\Phi(A,B)=AB-I_n\)，说明\(\Phi\in C^\infty(E^2)\). 给出\(\Phi\)的微分.</p>
        <p>3. 详述隐函数定理. 利用该定理和\(\Phi\)证明\(\varphi(M)=M^{-1}\)是\(U\)上的\(C^\infty\)映射，并由此计算\(\mathrm{d}\varphi(M)\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>记\(\mathrm{sh}\)为双曲正弦函数. 利用新变量\(u=x+y+z,uv=y+z,uvw=z\)计算积分.
        \[\iiint_{\{x,y,z>0,x+y+z<1\}}\mathrm{sh}\left[(x+y+z)^3\right]\mathrm{d}x\mathrm{d}y\mathrm{d}z.\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>考虑由极坐标方程\(r(\theta)=a\left(4\cos\theta-\dfrac{1}{\cos\theta}\right)\)定义的平面曲线\(\gamma_0\)，其中\(a>0\)是常数，\(\|\theta\|\le\dfrac{\pi}{3}.\)</p>
        <p>1. 勾画一个\(\gamma_0\)的图形.</p>
        <p>2. 计算曲线\(\gamma_0\)在\(\theta=\frac{\pi}{6}\)的切线方程，并在图中标出.</p>
        <p>3. 计算\(\gamma_0\)所围成的有界区域的面积.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>考虑函数
        \[G(x)=\int_0^1\frac{t-1}{\ln t}t^x\mathrm{d}t,\quad x>-1.\]</p>
        <p>1. 证明\(G\)在\(\Omega=(-1,\infty)\)上是恰当定义的且连续.</p>
        <p>2. 证明\(G\in C^1(\Omega)\)，计算\(G'(x)\)，推出\(G(x)\)的显式表达.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设\(f\)是\(\mathbb{R}^n\)到自身的\(C^1\)映射，且\(f\)是\(\lambda\)-Lipschitz，\(\lambda\in (0,1)\)，定义\(G(x)=x+f(x)\)</p>
        <p>1. 证明\(G\)是单射.</p>
        <p>2. 证明\(G(\mathbb{R}^n)\)既开又闭.</p>
        <p>3. 证明\(G\)是从\(\mathbb{R}^n\)到自身的\(C^1\)微分同胚.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>令\(\Gamma\)是Eular的Gamma函数，证明任给\(x,y>0\)，成立
        \[x^xy^y\Gamma\left(\frac{x+y}{2}\right)^2\le\left(\frac{x+y}{2}\right)^{x+y}\Gamma(x)\Gamma(y).\]</p>
      </div>
    </div>
  </div>
</details>

<div id="2023-fall-final" class="exam-header">
  <h3>2023秋季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（每题判断3分，理由2分）</p>
        <p>1. \(f(x,y)\)在原点的邻域\(U\)存在一阶偏导数，且\(\partial_x f,\partial_y f\)在\((0,0)\)处可微，则\(\frac{\partial^2}{\partial x\partial y}(0,0)=\frac{\partial^2}{\partial y\partial x}(0,0).\)</p>
        <p>2. \(\Omega\)是\(\mathbb{R}^2\)中的连通区域，\(F=(P,Q)\in C^1(\Omega,\mathbb{R}^2)\)，则\(\Omega\)上\(\partial_xQ-\partial_yP\equiv 0\)当且仅当\(F\)是\(\Omega\)上的梯度场.</p>
        <p>3. 设\(\mathbb{R}^3\)中的向量场\(F\)满足\(\mathrm{rot}(F)\)在Möbius带\(\mathcal{M}\)上恒为零，则\(F\)在\(\partial\mathcal{M}\)上的第二型曲线积分为零.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>考虑函数\(K:\Lambda=[0,1]^2\to\mathbb{R}\)，定义为\(\displaystyle K(x,y)=\frac{(1-x)(1-y)}{1-xy}\)若\((x,y)\neq (1,1)\)，\(K(1,1)=0\).</p>
        <p>1. 证明\(K\)在\(\Lambda\)上连续.</p>
        <p>2. \(K\)在\(\Lambda^o\)中是否有临界点？</p>
        <p>3. 确定\(\min_\Lambda K\)和\(\max_\lambda K\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>令\(D=\{(x,y)\in\mathbb{R}^2,x^2-y\le 0,y^2-x\le 0\}\). 利用变量替换\(u=x^2/y\)和\(v=y^2/x\)，计算
        \[\iint_D\exp\left(\frac{x^3+y^3}{xy}\right)\mathrm{d}x\mathrm{d}y.\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令\(\displaystyle\omega(x, y) = \frac{e^{-y}}{x^2 + y^2} \left[ (x \sin x - y \cos x)  \mathrm{d}x + (x \cos x + y \sin x)  \mathrm{d}y \right]\). 任给\(R > \epsilon > 0\)，记 \(\Omega_{\epsilon,R} = (B_R \backslash \overline{B_\epsilon}) \cap (\mathbb{R} \times (0, \infty))\), \(B_r\)为以原点为圆心半径\(r\)的开球.</p>
        <p>1. 画图表示\(\Omega_{\epsilon,R}\), 标注\(\partial \Omega_{\epsilon,R}\)的方向. 证明对任意\(R > \epsilon > 0\), \(\omega\)沿\(\partial \Omega_{\epsilon,R}\)的积分为零.</p>
        <p>2. 设\(r > 0\), 证明在参数化\((r \cos \theta, r \sin \theta)\)下, \(\omega \|_{\Gamma_r} = e^{-r \sin \theta} \cos(r \cos \theta)  \mathrm{d}\theta\).</p>
        <p>3. 记\(\Gamma_r = \partial B_r \cap (\mathbb{R} \times (0, \infty))\), 证明\(\left\|\displaystyle\lim_{r \to 0^+} \int_{\Gamma_r} \omega \right\|= \pi\) 和 \(\displaystyle\lim_{r \to \infty} \int_{\Gamma_r} \omega = 0\). 由此推出\(\displaystyle\int_0^\infty \frac{\sin x}{x}  \mathrm{d}x = \frac{\pi}{2}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>考虑\(yz\)平面中由\(y=f(x),z\in I=[a,b]\)定义的曲线\(\Gamma\)，设\( f\in C^1(I)\)且\(f>0\)，令\(\Sigma\)是由\(\Gamma\)绕\(z\)轴旋转一周得到的曲面.</p>
        <p>1. 证明\(\Sigma\)的面积公式为
        \[\mathcal{A}(\Sigma)=2\pi\int_a^b f(z)\sqrt{f'(z)^2+1}\mathrm{d}z.\]</p>
        <p>2. 设向量场\(\vec{v}(x,y,z)=(xz,yz,0)\)，取\(\Sigma\)的定向朝外，证明\(\vec{v}\)穿过\(\Sigma\)的通量等于\(\displaystyle 2\pi\int_a^b f(z)^2z\mathrm{d}z.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">16分</span>
      </div>
      <div class="math-content">
        <p>设\(f\)和\(g\)是\(\mathbb{R}_ +\)上的连续函数. 考虑\(f\)和\(g\)的卷积\(h=f * g\)，定义为
        \[h(x)=\int_0^x f(x-t)g(t)\mathrm t,\quad\forall x\ge 0\]</p>
        <p>1. 证明\(h\)在\(\mathbb{R}_ +\)上连续.</p>
        <p>2. 证明若\(f\)或\(g\)是\(\mathbb{R}_ +\)上的\(C^1\)函数，则\(h\)也是\(\mathbb{R}_ +\)上的\(C^1\)函数.</p>
        <p>3. 设\(f(x)\)满足\(\displaystyle\int_0^\infty\|f(x)\|\mathrm{d}x<\infty\)，且\(g\)在\(\mathbb{R}_ +\)上有界，证明\(h \)在\(\mathbb{R}_ +\)上有界.</p>
        <p>4. 令\(\displaystyle f_0(x)=\frac{\sin x}{x},g_0(x)=\cos x,h_0=f_0 * g_0\)是否在\(\mathbb{R}_ +\)有界？</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>已知一个平面凸四边形的相邻四边长度依次为\(5,6,7,8\)，试用Lagrange乘数法求该四边形可能的最大面积. （提示：不妨记长度\(5,6\)两边的内夹角为\(\theta\)，长度\(7,8\)两边的内夹角为\(\varphi\)，以此表达四边形的面积）.</p>
      </div>
    </div>
  </div>
</details>

<div id="2024-fall-final" class="exam-header">
  <h3>2024秋季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（每题判断3分，理由2分）</p>
        <p>1. 设 \( f \) 在 \( a \) 点的所有一阶和二阶偏导存在，那么 \(\frac{\partial^2 f}{\partial x_i \partial x_j}(a) = \frac{\partial^2 f}{\partial x_j \partial x_i}(a)\) 当且仅当 \( f \) 在 \( a \) 处二阶可微.</p>
        <p>2. 设 \(\Omega \subset \mathbb{R}^3\) 是分段光滑的有界区域.设 \( F \) 是 \(\Omega\) 上的 \( C^1 \) 向量场，\(\vec{n}\) 是 \(\partial \Omega\) 上的单位外法向量，则 \(\mathrm{rot}(F)\) 穿过 \(\partial \Omega\) 的通量为零.</p>
        <p>3. 设 \( I \subset \mathbb{R}\) 是闭区间，\( U, V \) 是 \(\mathbb{R}^n\) 中开集.设 \(\gamma: I \to U\) 是 \( C^1 \) 正则的参数曲线，\(\varphi: U \to V\) 是 \( C^1 \) 微分同胚，则曲线 \(\widetilde{\gamma} = \varphi \circ \gamma\) 的弧长 \(=\displaystyle \int_I \| \widetilde{\gamma}'(t) \| \cdot \| \det(\mathrm{Jac}_{\gamma(t)} \varphi)\|  \mathrm{d}t \).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>令 \( D = \{(x,y) \in \mathbb{R}^2 \mid x,y > 0, \frac{1}{2} < x + y < 1\} \)，计算 \[ \iint_D \exp \left( \frac{x - y}{x + y} \right)  \mathrm{d}x\mathrm{d}y.\]</p>
        <p>（提示：利用变量代换 \( u = x + y, v = x - y \)）</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>考虑函数 \( f : \mathbb{R}^n \to \mathbb{R} \)，证明 \( f \) 在 \(\mathbb{R}^n\) 上连续当且仅当 \( f \) 同时满足：</p>
        <p>1. 若 \( E \subset \mathbb{R}^n \) 是紧集，则 \( f(E) \) 是紧集；</p>
        <p>2. 若 \(\{E_k\}_ {k \in \mathbb{N}}\) 是\(\mathbb{R}^n\) 中紧集套（即 \(\forall k \in \mathbb{N}\), \(E_{k+1} \subset E_k\)），则 \( f(\cap_{k \in \mathbb{N}} E_k) = \cap_ {k \in \mathbb{N}} f(E_k) \).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令 \(\displaystyle \omega = \left[ \frac{2xy}{(1-x^2)^2 + y^2} - \cos x \right] \mathrm{d}x + \left[ \frac{1-x^2}{(1-x^2)^2 + y^2} + e^{3y} \right] \mathrm{d}y \).</p>
        <p>1. 给出 \(\omega\) 的定义域 \(\Omega\)，证明 \(\omega\) 在 \(\Omega\) 上是闭微分形式.</p>
        <p>2. 证明 \(\omega\) 在 \(\Omega\) 上是恰当的.</p>
        <p>3. 记 \(\Gamma\) 是沿曲线 \( y = \sin x \) 从 \((-\pi, 0)\) 到 \((2\pi, 0)\) 的路径，计算 \(\displaystyle\int_\Gamma \omega\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>固定 \( b \neq 0 \)，考虑 \(\displaystyle F(a) = \int_0^{+\infty} \frac{(1 - e^{-at}) \cos (bt)}{t}  \mathrm{d}t \).</p>
        <p>1. 确定广义积分 \( F \) 的定义域.</p>
        <p>2. 证明 \( F \) 在 \([0, +\infty)\) 上连续，在 \((0, +\infty)\) 上可导.</p>
        <p>3. 求 \( F(a) \) 的解析表达式.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \( P, Q, R \in C^1(\mathbb{R}^3) \) 满足：任取 \( a = (x_0, y_0, z_0) \in \mathbb{R}^3 \) 和 \( r > 0 \)，记 \(\Sigma_{a,r}\) 是以 \( a \) 为球心、\( r \) 为半径的上半球面，则 
        \[ \iint_{\Sigma_{a,r}} P  \mathrm{d}y \mathrm{d}z + Q  \mathrm{d}z \mathrm{d}x + R  \mathrm{d}x \mathrm{d}y = 0. \]</p>
        <p>证明：在 \(\mathbb{R}^3\) 上 \( R \equiv 0 \)，且 \(\dfrac{\partial P}{\partial x} + \dfrac{\partial Q}{\partial y}\equiv 0\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \( f : \mathbb{R}^n \to \mathbb{R}^n \) 是 \( C^1 \) 映射.证明：\(\mathrm{Jac}_x f\) 在 \(\mathbb{R}^n\) 上处处是对称矩阵当且仅当 \( f \) 是梯度场，即存在 \(\varphi \in C^2(\mathbb{R}^n)\) 使得 \( f = \nabla \varphi \).</p>
      </div>
    </div>
  </div>
</details>

<script>
// 添加一些交互功能
document.addEventListener('DOMContentLoaded', function() {
  // 为所有details元素添加切换动画
  const detailsElements = document.querySelectorAll('details');
  
  detailsElements.forEach(details => {
    details.addEventListener('toggle', function() {
      if (this.open) {
        this.style.transition = 'all 0.3s ease';
      }
    });
  });
  
  // 平滑滚动到锚点
  const links = document.querySelectorAll('a[href^="#"]');
  links.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const targetId = this.getAttribute('href');
      const targetElement = document.querySelector(targetId);
      if (targetElement) {
        targetElement.scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });
      }
    });
  });
});
</script>
