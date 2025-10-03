---
title: "高等代数I"
collection: exams
type: "专业必修课程"
permalink: /exams/Advanced-algebra1
venue: "ECNU"
date: 2024-01-24
location: "Shanghai, China"
grade: 1.0
a: 大一上
instructor: 陆俊教授
---

<div class="exam-toc">
  <h2>试卷目录</h2>
  <ul>
    <li><a href="#2023-fall-midterm">2023秋季学期期中考试</a></li>
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

<div id="2023-fall-midterm" class="exam-header">
  <h3>2023秋季学期期中考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="math-content">
      <p>以下如无特别声明，\(K\)均表数域，\(\mathbb{Q}(\mathbb{R},\mathbb{C})\)表有理数（实数、复数）域，\(f,g\)表\(K[x]\)中的多项式</p>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>考虑置换\[\sigma=\left (\begin{matrix}1&2&3&4&5&6&7&8\\4&8&3&1&6&8&5&2\end{matrix}\right ),\quad \tau=\left(\begin{matrix}1&2&3&4&5&6&7&8\\3&7&1&8&6&4&2&5\end{matrix}\right).\]</p>
        <p>求乘积\(\tau^{-1}\sigma^{-1}\tau\sigma\).</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>考虑\(n\)元对称多项式\[f(x_1,x_2,\cdots,x_n)=\sum_{1\le i<j\le n}(x_i+x_j)^3.\]</p>
        <p>将\(f\)写为初等对称多项式\(\mathrm{e}_1,\mathrm{e}_2,\cdots,\mathrm{e}_n\)的表达式.</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设\[\begin{align}f(x)=&x^5+x^4+2x^3-x^2-x-2,\\g(x)=&x^4+x^2-x-1\end{align}\]</p>
        <p>1. 利用辗转相除法求\(f(x),g(x)\)的最大公因式\((f,g)\)（需写出辗转相除法过程）；</p>
        <p>2. 求次数最小的\(u,v\in \mathbb{Q}[x]\)，满足\(uf+vg=(f,g)\).</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>求次数最小的多项式\(f(x)\in K[x]\)，满足如下方程组</p>
        <p>\[\begin{cases} f(x)\equiv 2x+4&\pmod{x+1},\\f(x)\equiv 2x^2+2x&\pmod{x^2+1},\\f(x)\equiv 3x^2+1&\pmod{x^3}.\end{cases}\]</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设\[f(x)=8x^6+4x^5-14x^4-9x^3+5x^2+5x+1.\]</p>
        <p>1. 求\(f(x)\)的所有有理根，并指出它们的重数；</p>
        <p>2. 求\(f(x)\)在\(x=1\)处的Taylor展开式.</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明：\(f(x)=x^{n-1}+x^{n-2}+\cdots+x+1\)是\(\mathbb{Q}[x]\)中的不可约多项式当且仅当\(n\)是素数.</p>
      </div>
    </div>
    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\(f(x)\in K[x]\)无重因式，\(n\ge 2\)是给定正整数，证明：\(f(x^n)\)有重因式当且仅当\(x=0\)是\(f(x)\)的单根.</p>
      </div>
    </div>
    <div class="optional">
      <div class="optional-title">
        <span>可选附加题 - Mason定理</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\(f(x)\in\mathbb{C}[x]\)，用\(n_0(f)\)表示多项式\(f(x)\)的不同根的个数.</p>
        <p>假设\(g,h\in \mathbb{C}[x]\)满足\(f+g+h=0\)以及\((g,h)=1\)，证明\[\max\{\deg f,\deg g,\deg h\}\le n_0(fgh)-1.\]</p>
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
