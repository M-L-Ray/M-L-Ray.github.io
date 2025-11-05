---
title: "高等代数II(H)"
collection: exams
type: "专业必修课程"
permalink: /exams/Advanced-algebra2h
venue: "ECNU"
date: 2024-06-24
location: "Shanghai, China"
grade: 1.5
a: 大一下
instructor: 罗栗教授
---

<div class="exam-toc">
  <h2>试卷目录</h2>
  <ul>
    <li><a href="#2024-spring-final">2024春季学期期末考试</a></li>
    <li><a href="#2025-spring-mid">2025春季学期期中考试</a></li>
  </ul>
</div>

<style>
.exam-toc {
  background: transparent;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 2rem 0;
  border-left: 4px solid #4285f4;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.exam-toc h2 {
  margin-top: 0;
  color: inherit;
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
  background: rgba(0, 0, 0, 0.05);
}

.exam-toc a {
  text-decoration: none;
  color: #4285f4;
  font-weight: 500;
  display: block;
}

.exam-header {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.9) 0%, rgba(118, 75, 162, 0.9) 100%);
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
  background: transparent;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  margin: 1.5rem 0;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  transition: box-shadow 0.3s;
}

details:hover {
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

summary {
  background: transparent;
  padding: 1.2rem 1.5rem;
  cursor: pointer;
  font-weight: 600;
  color: inherit;
  border-radius: 8px 8px 0 0;
  font-size: 1.1rem;
  border-bottom: 1px solid rgba(0, 0, 0, 0.05);
}

details[open] summary {
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
}

.exam-content {
  padding: 1.5rem;
}

.question {
  margin: 1.5rem 0;
  padding: 1rem;
  background: transparent;
  border-radius: 6px;
  border-left: 3px solid #4285f4;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

.question-title {
  font-weight: 600;
  color: inherit;
  margin-bottom: 0.8rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.points {
  background: #4285f4;
  color: white;
  padding: 0.2rem 0.6rem;
  border-radius: 20px;
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

.solution {
  margin: 1rem 0;
}

.solution summary {
  background: transparent;
  padding: 0.8rem 1rem;
  cursor: pointer;
  font-weight: 600;
  color: inherit;
  border-radius: 4px;
  font-size: 1rem;
  border: 1px solid rgba(0, 0, 0, 0.1);
  margin-bottom: 0;
}

.solution summary:hover {
  background: rgba(0, 0, 0, 0.02);
}

.solution-content {
  padding: 1rem;
  border-left: 2px solid rgba(0, 0, 0, 0.1);
  margin-top: 0.5rem;
}

.proof {
  background: transparent;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 6px;
  padding: 1rem;
  margin: 1rem 0;
}

.proof-title {
  font-weight: 600;
  color: inherit;
  margin-bottom: 0.5rem;
}

.optional {
  background: rgba(232, 245, 232, 0.5);
  border: 1px solid rgba(76, 175, 80, 0.5);
  border-radius: 6px;
  padding: 1rem;
  margin: 1rem 0;
}

.optional-title {
  font-weight: 600;
  color: #2e7d32;
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

<div id="2024-spring-final" class="exam-header">
  <h3>2024春季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>判断下列命题正误，并说明理由：</p>
        <p>(1) 两个正交矩阵之和还是正交矩阵；</p>
        <p>(2) 两个矩阵的特征值及其代数重数完全相同，则它们相似；</p>
        <p>(3) 两个实对称矩阵相似，则它们相合；</p>
        <p>(4) 复矩阵 \( A,B \) 满足 \( A^2 \sim B^2 \)，则 \( A \sim B \). </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>求三阶实对称矩阵 \( A \)，其特征值为 \( 6,3,3 \)，其中特征值 \(6\) 对应的一个特征向量为 \( (1,1,1)^T \). </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>定义 \( M_2(\mathbb{R}) \times M_2(\mathbb{R}) \to \mathbb{R} \) 的函数：\( f(A,B) = |A+B| - |A| - |B| \). </p>
        <p>(1) 证明 \( f \) 是对称双线性函数；</p>
        <p>(2) 求 \( f \) 在 \( E_{11}, E_{12}, E_{21}, E_{22} \) 下的度量矩阵，并求 \( f \) 的符号差. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>已知 \( A = \begin{pmatrix} 0 & 2024 & 6 \\ & 0 & 24 \\ & & 0 \end{pmatrix} \)，求证方程 \( X^2 = A \) 无解（\( X \in M_3(\mathbb{C}) \)）. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>求矩阵 \( A = \begin{pmatrix} -4 & 3 & 0 & 0 \\ -3 & 2 & 0 & 0 \\ 5 & 1 & 1 & -2 \\ 2 & 0 & 2 & -3 \end{pmatrix} \) 的初等因子，不变因子以及 Jordan 标准型. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>已知线性空间 \( V \) 上的线性函数 \( f, f_1, f_2, \cdots, f_k \in \text{Hom}(V,\mathbb{K}) \) 满足当 \( f_1(\alpha) = f_2(\alpha) = \cdots = f_k(\alpha) \) 时都有 \( f(\alpha) = 0 \)，求证 \( f \) 是 \( f_1, f_2, \cdots, f_k \) 的线性组合. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>已知矩阵 \( A \in M_n(\mathbb{C}) \) 有 \( n \) 个不同的特征值 \( \lambda_1, \lambda_2, \cdots, \lambda_n \)，定义变换 \( \text{ab}_A(B) = A B - B A \). </p>
        <p>(1) 求证 \( \text{ab}_A \) 是 \( M_n(\mathbb{C}) \) 上的线性变换；</p>
        <p>(2) 求线性变换 \( \text{ab}_A \) 的 \( n^2 \) 个特征值. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第8题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>定义对角线全为 1 的 \( m \) 阶复上三角矩阵全体为 \( N_m^+ \)，对角线全为 1 的 \( n \) 阶复下三角矩阵全体为 \( N_n^- \)，定义 \( M_{m \times n}(\mathbb{C}) \) 上的关系 \( A \sim B \)：\( \exists P \in N_m^+, Q \in N_n^- \) 使得 \( A = P B Q \). </p>
        <p>(1) 求证该关系是 \( M_{m \times n}(\mathbb{C}) \) 上的等价关系；</p>
        <p>(2) \( \Delta_i \) 定义为 \( A \) 的 \( i \) 阶顺序主子式，求证：\( \Delta_1, \cdots, \Delta_{\min\{m,n\}} \) 是上述等价关系的不变量. </p>
      </div>
    </div>
  </div>
</details>

<div id="2025-spring-mid" class="exam-header">
  <h3>2025春季学期期中考试</h3>
  <div class="exam-meta">总分：110分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="math-content">
      <p><strong>本次考试的数学目标是给出代数基本定理的一种证明. （Harm Derksen,2003）</strong></p>
      
      <div class="proof">
        <div class="proof-title">定理1</div>
        <p>令 \( f(x)\in\mathbb{C}[x] \) 且 \(\deg f>0\)，则存在 \(\alpha\in\mathbb{C}\) 使得 \(f(\alpha)=0\). </p>
      </div>

      <h4>-准备-</h4>
      <p>我们不妨设 \(f(x)=\displaystyle\sum_{i=0}^na_ix^i\)，其中 \(a_n=1,n\ge 1\). 令 \(\overline{f}(x)=\displaystyle\sum_{i=0}^n\overline{a_i}x^i\)，其中 \(\overline{a_i}\) 是 \(a_i\) 的共轭复数. </p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题一</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令 \(g(x)=f(x)\cdot\overline{f}(x)\)，证明：</p>
        <p>1. \(g(x)\in\mathbb{R}[x]\). </p>
        <p>2. \(f\) 有复根当且仅当 \(g\) 有复根. </p>
      </div>
    </div>

    <div class="math-content">
      <p>由题一，我们下面可以用 \(g\) 替换 \(f\)，总是假定 \(f(x)\in\mathbb{R}[x]\). 考虑实 \(n\) 级矩阵 \(A=(c_{ij})\) 满足 \(c_{in}=-a_{i-1}\)，对任意 \(1\le i\le n\)，\(c_{i,i-1}=1\)，对任意 \(2\le i\le n\)，其余地方为 \(0\). 容易验证 \(A\) 的特征多项式为 \(f(x)\). </p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题二</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>令 \(f(x)=x^2-1\). 写出如上构造的矩阵 \(A\). </p>
      </div>
    </div>

    <div class="math-content">
      <p>于是，代数学基本定理等价于如下定理. 所以我们只专注于定理2的证明. </p>
      
      <div class="proof">
        <div class="proof-title">定理2</div>
        <p>任何 \(n\) 级<strong>实</strong>方阵 \(A\)（线性映射）都存在（复）特征向量. </p>
      </div>

      <p>令 \(n\) 是一个正整数，由唯一分解，我们可以写 \(n=2^{r_2}\cdot 3^{r_3}\cdots\). 定义 \(v_2(n):=r_2\). </p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题三</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>用数分证明"初始"情形：当 \(v_2(n)=0\) 时，定理1（所以定理2）成立. </p>
      </div>
    </div>

    <div class="math-content">
      <h4>-进阶-</h4>
      <p>令 \(M\) 是所有 \(n\) 级复方阵构成的线性空间. 则 \(A\) 诱导了两个线性映射 \(L:M\to M\) 通过 \(X\mapsto A^TX\) 以及 \(R:M\to M\) 通过 \(X\mapsto XA\). </p>
      <p>令 \(S\) 是所有 \(n\) 级<strong>复对称</strong>方阵构成的线性子空间. 我们又有两个自然生成的线性映射 \(\alpha:S\to S\) 通过 \(X\mapsto L(X)+R(X)=A^TX+XA\)，以及 \(\beta:S\to S\) 通过 \(X\mapsto L\circ R(X)=R\circ L(X)=A^TXA\). </p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题四</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>令 \(v_2(n)=r\). 证明 \(\dim S=\frac{n(n+1)}{2}\) 以及 \(v_2(\dim S)<r\). </p>
      </div>
    </div>

    <div class="math-content">
      <p>我们对 \(v_2(n)\) 归纳，初始情形已由题三给出，现在可假设<strong>定理2对于 \(v_2(n)<r\) 情形成立</strong>. </p>
      <p>我们考虑 \(v_2(n)=r\) 情形. 由题四，\(\alpha,\beta\) 都有（复）特征向量. </p>
      <p>但这不够，我们需要证明 \(\alpha,\beta\) 有公共特征向量：</p>
      
      <div class="proof">
        <div class="proof-title">引理3</div>
        <p>存在 \(0\neq X\in S,\lambda,\mu\in\mathbb{C}\) 使得 \(\alpha(X)=\lambda X,\beta(X)=\mu X\). </p>
      </div>

      <p>令 \(S_\lambda\) 是 \(\alpha\) 的 \(\lambda\)-特征子空间，令 \(I_\lambda=\mathrm{Im}(\lambda\cdot\mathrm{id}-\alpha)\). 显然 \(\alpha(S_\lambda)\subseteq S_{\lambda}\) 以及 \(\alpha(I_\lambda)\subseteq I_\lambda\). </p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题五</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>严格证明：</p>
        <p>1. \(\beta(S_\lambda)\subset S_\lambda,\beta(I_\lambda)\subseteq I_\lambda\). </p>
        <p>2. \(\min\{v_2(\dim S_\lambda),v_2(\dim I_\lambda)\}\le v_2(\dim S)\). </p>
        <p>3. 如果 \(v_2(\dim S_\lambda)\le v_2(\dim S)\)，那么 \(\alpha|_{S_\lambda},\beta|_{S_\lambda}\) 有公共特征向量. </p>
        <p>4. 如果 \(v_2(\dim S_\lambda)> v_2(\dim S)\)，那么 \(\alpha|_{I_\lambda},\beta|_{I_\lambda}\) 有公共特征向量. （注意，这里特征值可能会变）</p>
      </div>
    </div>

    <div class="math-content">
      <p>如题五，我们完成了引理3的证明. </p>

      <h4>-终章-</h4>
      <p>令 \(t\) 是二次方程 \(x^2-\lambda x+\mu =0\) 的一个复根. 考虑如下映射</p>
      <p>\[\varphi:=(t\cdot\mathrm{id}-L)\circ (t\cdot \mathrm{id}-R):M\to M\]</p>
    </div>

    <div class="question">
      <div class="question-title">
        <span>题六</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>证明：</p>
        <p>1. \(\varphi(X)=0\)，其中 \(X\) 由引理3所得. </p>
        <p>2. \(t\) 是 \(L\) 或者 \(R\) 的特征值. </p>
        <p>3. \(t\) 是 \(A\) 的特征值. （我们完成了代数基本定理的证明！）</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>附加题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>详细阐述作者是如何证明 \(f(x)=x^2-1\) 有根的？（需要写出 \(L\) 和 \(R\) 的特征多项式）</p>
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
