---
title: "实分析"
collection: exams
type: "专业必修课程"
permalink: /exams/real_analysis
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
grade: 2.5
a: 大二下
instructor: 袁海荣教授
---

<div class="exam-toc">
  <h2>试卷目录</h2>
  <ul>
    <li><a href="#2024-spring-test1">2024春季学期第一次小测</a></li>
    <li><a href="#2025-spring-test2">2025春季学期第二次小测</a></li>
    <li><a href="#2025-spring-final">2025春季学期期末考试</a></li>
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
  background: rgba(255, 243, 224, 0.5);
  border: 1px solid rgba(255, 183, 77, 0.5);
  border-radius: 6px;
  padding: 1rem;
  margin: 1rem 0;
}

.proof-title {
  font-weight: 600;
  color: #e65100;
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

<div id="2024-spring-test1" class="exam-header">
  <h3>2024春季学期第一次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>请叙述并证明Borel-Cantelli定理. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \(X=\mathbb{R}\)，定义 \(2^X\) 上的集函数</p>
        <p>$$\mu(A)=\begin{cases}1,&0\in A, \\ 0,&0\notin A.\end{cases}$$</p>
        <p>证明 \(\mu\) 是一个测度. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \(\mathcal{R}\) 是基本空间 \(X\) 上的 \(\sigma\)-环，\(\mu\) 是 \(\mathcal{R}\) 上非负的满足有限可加性和次可列可加性的集函数，且 \(\mu(\varnothing)=0\). 证明 \(\mu\) 是一个测度. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设集 \(E\) 上的实函数列 \(f_n\) 有极限 \(f\)，证明：对任意实数 \(c\)，成立</p>
        <p>\[E(f\le c)=\bigcap_{k=1}^\infty\liminf_{n\to\infty}E(f_n\le c+\frac{1}{k}).\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设 \(X=\mathbb{R}\)，定义 \(2^X\) 上的集函数 \(\mu_*\) 使得 \(\mu_* (\varnothing)=0\)，而当 \(A\neq\varnothing\) 时，\(\mu_*(A)=1\). </p>
        <p>1. 证明：\(\mu_*\) 是次可列可加的；</p>
        <p>2. 写出：\(\mu_*\) 可测集的 Caratheodory 条件；</p>
        <p>3. 证明：\(\mu_*\) 可测集构成的 \(\sigma\)-代数是 \(\{\varnothing,X\}\). </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>证明：任意可列集的有限子集的全体仍然是可列集. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题</span>
        <span class="points">30分</span>
      </div>
      <div class="math-content">
        <p>设 \(X\) 是基本空间</p>
        <p>1. \(\mathcal{P}\subset 2^X,\mathcal{P}\neq\varnothing\)，如果由 \(A,B\in\mathcal{P}\) 可知 \(A\cap B\in\mathcal{P}\)，则称 \(\mathcal{P}\) 是一个 \(\pi\)-系. </p>
        <p>2. \(\mathcal{L}\subset 2^X,\mathcal{L}\neq\varnothing\) 称为一个 \(\lambda\)-系，若其具有如下性质：</p>
        <ul>
          <li>\(X\in\mathcal{L}\);</li>
          <li>若 \(A,B\in \mathcal{L}\) 且 \(A\subset B\)，则 \(B-A\in \mathcal{L}\)；</li>
          <li>若 \(A_k\in\mathcal{L},k=1,2,\dots\)，且 \(A_{k}\subset A_{K+1}\)，则 \(\bigcup_{k=1}^\infty A_k\in\mathcal{L}\). </li>
        </ul>
        <p>请按如下步骤证明如下 \(\underline{\pi-\lambda\text{定理}}\)：设 \(\mathcal{P}\) 是 \(\pi\)-系，\(\mathcal{L}\) 是 \(\lambda\)-系，且 \(\mathcal{P}\subset\mathcal{L}\)，则 \(S(\mathcal{P})\subset \mathcal{L}\). 这里 \(S(\mathcal{P})\) 是 \(\mathcal{P}\) 生成的 \(\sigma\)-代数. </p>
        <p>3. 定义 \(\mathcal{S}=\bigcap_{\mathcal{L}'\supset \mathcal{P}}\mathcal{L}'\)，其中 \(\mathcal{L}'\) 是 \(\lambda\)-系. 证明 \(\mathcal{S}\) 是包含 \(\mathcal{P}\) 的最小的 \(\lambda\)-系. </p>
        <p>4. 下面证明 \(\mathcal{S}\) 是 \(\pi\)-系. 为此，作 \(\mathcal{A}=\{C\subset X:A\cap C\in\mathcal{S}\}\). 证明：当 \(A\in\mathcal{P}\) 时，成立 \(\mathcal{P}\subset\mathcal{A}\). </p>
        <p>5. 请进一步证明：当 \(A\in \mathcal{S}\) 时，\(\mathcal{A}\) 是 \(\lambda\)-系. </p>
        <p>6. 由此证明：\(\mathcal{S}\subset\mathcal{A}\)，并证明 \(\mathcal{S}\) 是 \(\pi\)-系. </p>
        <p>7. 证明：\(\mathcal{S}\) 是 \(\sigma\)-代数. </p>
        <p>8. 证明：\(S(\mathcal{P})\subset \mathcal{L}\). </p>
      </div>
    </div>
  </div>
</details>

<div id="2025-spring-test2" class="exam-header">
  <h3>2025春季学期第二次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>证明：对任何给定的非负可测函数，都存在一列非负的单调递增的简单函数列处处收敛于它. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>叙述并证明积分的全连续性. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>叙述并证明 Lebesgue 控制收敛定理. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>叙述并证明积分的可列可加性. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设 \((X,\mathcal{R},\mu)\) 是一个 \(\sigma\)-有限测度空间，\(E\in\mathcal{R}\)，\(f_n\) 是 \(E\) 上一列可测函数，且</p>
        <p>\[\lim_{m,n\to\infty}\int_E|f_m-f_n|^2\mathrm{d}\mu=0.\]</p>
        <p>证明：存在 \(E\) 上的可测函数 \(f\)，使得</p>
        <p>\[\lim_{m,n\to\infty}\int_E|f_m-f|^2\mathrm{d}\mu=0.\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设 \(f\) 是区间 \([0,1]\) 上的连续函数，证明：</p>
        <p>\[\lim_{n\to\infty}\int_0^1\cdots\int_0^1f(\frac{x_1+\cdots+x_n}{n})\mathrm{d}x_1\cdots \mathrm{d}x_n=f(\frac{1}{2}).\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \(E\) 是测度空间 \((X,\mathcal{R},\mu)\) 上测度有限的集. 证明：函数 \(f\) 在 \(E\) 上可积的充分必要条件是 \(\sum_{n=1}^\infty n\mu(E_n)<\infty\)，其中 \(E_n=E(n\le\|f\|<n+1)\). </p>
      </div>
    </div>
  </div>
</details>

<div id="2025-spring-final" class="exam-header">
  <h3>2025春季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>叙述并证明 Helly 选取原理. </p>
      </div>
    </div>
    
    <div class="question">
      <div class="question-title">
        <span>第2题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>叙述并证明 Hahn 分解定理. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>证明 \([a,b]\) 上的有界变差函数全体与实数集等势. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题</span>
        <span class="points">15分</span>
      </div>
      <div class="math-content">
        <p>设 \(f\) 是 \((-\infty,+\infty)\) 上满足 \(f(0)=0\) 的 Lebesgue 可积函数，证明 \(\displaystyle\sum_{n=-\infty}^{+\infty}f(n^2x)\) 必在 \((-\infty,+\infty)\) 上几乎处处（按 Lebesgue 测度）等于一个 Lebesgue 可积函数. </p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设 \((X,\mathcal{S},\mu),(Y,\mathcal{T},\nu)\) 是两个全有限测度空间，如果 \(E\) 是 \((X\times Y,\mathcal{S}\times\mathcal{T})\) 的可测子集，证明：\(\nu(E_x),\mu(E^y)\) 分别是 \((X,\mathcal{S},\mu),(Y,\mathcal{T},\nu)\) 上的可测函数，且</p>
        <p>\[\int_X\nu(E_x)\mathrm{d}\mu=\int_Y\mu(E^y)\mathrm{d}\nu.\]</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>证明 Лузин（鲁津）定理. </p>
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
