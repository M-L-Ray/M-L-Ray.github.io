---
title: "常微分方程"
collection: exams
type: "专业必修课程"
permalink: /exams/ODE
venue: "ECNU"
date: 2025-10-16
location: "Shanghai, China"
grade: 2.0
a: 大二上
instructor: 张静副教授
---

<div class="exam-toc">
  <h2>试卷目录</h2>
  <ul>
    <li><a href="#2025-fall-test1">2025秋季学期第一次小测</a></li>
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
  border: none; /* 去掉边框 */
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
  border-radius: 8px;
  font-size: 1.1rem;
  border: none; /* 去掉边框 */
}

details[open] summary {
  border-bottom: none; /* 去掉打开时的底部边框 */
}

.exam-content {
  padding: 1.5rem;
}

.question {
  margin: 1.5rem 0;
  padding: 1rem;
  background: transparent;
  border-radius: 6px;
  border: none; /* 去掉边框 */
  box-shadow: none; /* 去掉阴影 */
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
  border: none; /* 去掉边框 */
  margin-bottom: 0;
}

.solution summary:hover {
  background: rgba(0, 0, 0, 0.02);
}

.solution-content {
  padding: 1rem;
  border-left: none; /* 去掉左侧边框 */
  margin-top: 0.5rem;
}

.proof {
  background: transparent; /* 改为透明背景 */
  border: none; /* 去掉边框 */
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
  background: transparent; /* 改为透明背景 */
  border: none; /* 去掉边框 */
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

<div id="2025-fall-test1" class="exam-header">
  <h3>2025秋季学期第一次小测 </h3>
  <div class="exam-meta">考试时间：2025.10.16 8:00-8:50 | 总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="math-content">
      <p>以下如无特别声明，微分方程均在适当定义域内求解。</p>
    </div>
    
    <div class="question">
      <div class="question-title">
        <span>第1题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>求解微分方程：</p>
        <p>\[2x(y\mathrm{e}^{x^2}-1)\mathrm{d}x+\mathrm{e}^{x^2}\mathrm{d}y=0\]</p>
      </div>
      <details class="solution">
        <summary>参考解答</summary>
        <div class="solution-content">
          <div class="math-content">
            <p>恰当方程，\(y\mathrm{e}^{x^2}-x^2=C,\ C\in\mathbb{R}.\)</p>
          </div>
        </div>
      </details>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>求解积分方程：</p>
        <p>\[y=\mathrm{e}^x+\int_0^x y(t)\mathrm{d}t\]</p>
      </div>
      <details class="solution">
        <summary>参考解答</summary>
        <div class="solution-content">
          <div class="math-content">
            <p>求导得\(y'=\mathrm{e}^x+y\)，且有初值\(y(0)=1\)，解得\(y=(x+1)\mathrm{e}^x.\)</p>
          </div>
        </div>
      </details>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>求解微分方程：</p>
        <p>\[(y-1-xy)\mathrm{d}x+x\mathrm{d}y=0\]</p>
      </div>
      <details class="solution">
        <summary>参考解答</summary>
        <div class="solution-content">
          <div class="math-content">
            <p>\(\dfrac{Q_x-P_y}{Q}=1\Rightarrow\)积分因子\(\mathrm{e}^{-x}\)，解得\((xy+1)\mathrm{e}^{-x}=C,\ C\in\mathbb{R}.\)</p>
          </div>
        </div>
      </details>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>求解微分方程：</p>
        <p>\[y=\left(\frac{\mathrm{d}y}{\mathrm{d}x}\right)^2-x\left(\frac{\mathrm{d}y}{\mathrm{d}x}\right)+\frac{x^2}{2}\]</p>
      </div>
      <details class="solution">
        <summary>参考解答</summary>
        <div class="solution-content">
          <div class="math-content">
            <p>换元\(p=y'\)，两侧求导可得\((2p-x)(p'-1)=0\Rightarrow y=\dfrac{1}{4}x^2\)或\(\dfrac{1}{2}x^2+C x+C^2,C\in\mathbb{R}.\)</p>
          </div>
        </div>
      </details>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>设\(f(x)\)在\(\mathbb{R}\)上有界，\(f(x)+f'(x)=g(x)\)，且\(|g(x)|\le M\)，证明：</p>
        <p>\[|f(x)|\le M\]</p>
      </div>
      <details class="solution">
        <summary>参考解答</summary>
        <div class="solution-content">
          <div class="math-content">
            <p>\(\displaystyle f(x)=\frac{C+\int_{-\infty}^x g(t)\mathrm{e}^t\mathrm{d} t}{\mathrm{e}^x}\)，有界（考虑\(x\to-\infty\)）\(\Rightarrow C=0\)，从而\(\displaystyle|f(x)|=\frac{|\int_{-\infty}^xg(t)\mathrm{e}^t\mathrm{d} t|}{\mathrm{e}^x}\le\)\(\displaystyle\frac{\int_{-\infty}^x|g(t)|\mathrm{e}^t\mathrm{d} t}{\mathrm{e}^x}\le M.\)</p>
          </div>
        </div>
      </details>
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
