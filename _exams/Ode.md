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
  background: rgba(232, 245, 232, 0.3);
  border: 1px solid rgba(76, 175, 80, 0.3);
  border-radius: 6px;
  padding: 1rem;
  margin: 1rem 0;
}

.solution-title {
  font-weight: 600;
  color: #2e7d32;
  margin-bottom: 0.5rem;
  display: flex;
  align-items: center;
}

.solution-title::before {
  content: "💡";
  margin-right: 0.5rem;
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

<div id="2025-fall-test1" class="exam-header">
  <h3>ODE第一次小测（非师范班）</h3>
  <div class="exam-meta">考试时间：2025.10.16 8:00-8:50 | 总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="math-content">
      <p>以下如无特别声明，微分方程均在适当定义域内求解. </p>
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
      <div class="solution">
        <div class="solution-title">参考解答</div>
        <div class="math-content">
          <p>该方程为恰当微分方程. 验证：</p>
          <p>令 \(M = 2x(y\mathrm{e}^{x^2}-1)\)，\(N = \mathrm{e}^{x^2}\)</p>
          <p>则 \(\frac{\partial M}{\partial y} = 2x\mathrm{e}^{x^2}\)，\(\frac{\partial N}{\partial x} = 2x\mathrm{e}^{x^2}\)</p>
          <p>由于 \(\frac{\partial M}{\partial y} = \frac{\partial N}{\partial x}\)，方程为恰当微分方程. </p>
          <p>设存在函数 \(u(x,y)\) 使得：</p>
          <p>\[\frac{\partial u}{\partial x} = M = 2x(y\mathrm{e}^{x^2}-1)\]</p>
          <p>\[\frac{\partial u}{\partial y} = N = \mathrm{e}^{x^2}\]</p>
          <p>由第二式积分得：\(u = y\mathrm{e}^{x^2} + h(x)\)</p>
          <p>代入第一式：\(\frac{\partial u}{\partial x} = 2xy\mathrm{e}^{x^2} + h'(x) = 2xy\mathrm{e}^{x^2} - 2x\)</p>
          <p>解得：\(h'(x) = -2x\)，积分得 \(h(x) = -x^2 + C\)</p>
          <p>因此通解为：\(y\mathrm{e}^{x^2} - x^2 = C\)，其中 \(C \in \mathbb{R}\)</p>
        </div>
      </div>
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
      <div class="solution">
        <div class="solution-title">参考解答</div>
        <div class="math-content">
          <p>对方程两边求导：</p>
          <p>\[y' = \mathrm{e}^x + y\]</p>
          <p>原方程中令 \(x = 0\) 得初值条件：\(y(0) = \mathrm{e}^0 + 0 = 1\)</p>
          <p>求解一阶线性微分方程：\(y' - y = \mathrm{e}^x\)</p>
          <p>积分因子：\(\mu(x) = \mathrm{e}^{\int -1\mathrm{d}x} = \mathrm{e}^{-x}\)</p>
          <p>方程化为：\((\mathrm{e}^{-x}y)' = 1\)</p>
          <p>积分得：\(\mathrm{e}^{-x}y = x + C\)</p>
          <p>由初值 \(y(0) = 1\) 得：\(1 = 0 + C\)，即 \(C = 1\)</p>
          <p>因此解为：\(y = (x + 1)\mathrm{e}^x\)</p>
        </div>
      </div>
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
      <div class="solution">
        <div class="solution-title">参考解答</div>
        <div class="math-content">
          <p>原方程写为：\((y-1)\mathrm{d}x - xy\mathrm{d}x + x\mathrm{d}y = 0\)</p>
          <p>即：\((y-1)\mathrm{d}x + x(\mathrm{d}y - y\mathrm{d}x) = 0\)</p>
          <p>验证是否为恰当微分方程：</p>
          <p>令 \(M = y-1-xy\)，\(N = x\)</p>
          <p>\(\frac{\partial M}{\partial y} = 1 - x\)，\(\frac{\partial N}{\partial x} = 1\)</p>
          <p>由于 \(\frac{\partial M}{\partial y} \neq \frac{\partial N}{\partial x}\)，方程不恰当. </p>
          <p>计算：\(\frac{\frac{\partial M}{\partial y} - \frac{\partial N}{\partial x}}{N} = \frac{(1-x)-1}{x} = -1\)</p>
          <p>积分因子：\(\mu(x) = \mathrm{e}^{\int -1\mathrm{d}x} = \mathrm{e}^{-x}\)</p>
          <p>乘以积分因子后方程变为恰当方程：</p>
          <p>\[\mathrm{e}^{-x}(y-1-xy)\mathrm{d}x + x\mathrm{e}^{-x}\mathrm{d}y = 0\]</p>
          <p>设存在函数 \(u(x,y)\) 使得：</p>
          <p>\[\frac{\partial u}{\partial x} = \mathrm{e}^{-x}(y-1-xy)，\quad \frac{\partial u}{\partial y} = x\mathrm{e}^{-x}\]</p>
          <p>由第二式积分得：\(u = xy\mathrm{e}^{-x} + h(x)\)</p>
          <p>代入第一式验证可得通解为：\((xy+1)\mathrm{e}^{-x} = C\)，其中 \(C \in \mathbb{R}\)</p>
        </div>
      </div>
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
      <div class="solution">
        <div class="solution-title">参考解答</div>
        <div class="math-content">
          <p>令 \(p = \frac{\mathrm{d}y}{\mathrm{d}x}\)，则原方程为：</p>
          <p>\[y = p^2 - xp + \frac{x^2}{2}\]</p>
          <p>两边对 \(x\) 求导：</p>
          <p>\[p = 2p\frac{\mathrm{d}p}{\mathrm{d}x} - p - x\frac{\mathrm{d}p}{\mathrm{d}x} + x\]</p>
          <p>整理得：\((2p - x)\frac{\mathrm{d}p}{\mathrm{d}x} = 2p - x\)</p>
          <p>即：\((2p - x)(\frac{\mathrm{d}p}{\mathrm{d}x} - 1) = 0\)</p>
          <p>情况1：\(2p - x = 0\)，即 \(p = \frac{x}{2}\)</p>
          <p>代入原方程：\(y = \left(\frac{x}{2}\right)^2 - x\cdot\frac{x}{2} + \frac{x^2}{2} = \frac{x^2}{4}\)</p>
          <p>情况2：\(\frac{\mathrm{d}p}{\mathrm{d}x} = 1\)，即 \(p = x + C\)</p>
          <p>代入原方程：\(y = (x+C)^2 - x(x+C) + \frac{x^2}{2} = x^2 + 2Cx + C^2 - x^2 - Cx + \frac{x^2}{2}\)</p>
          <p>整理得：\(y = \frac{1}{2}x^2 + Cx + C^2\)，其中 \(C \in \mathbb{R}\)</p>
          <p>因此方程的通解为：\(y = \frac{1}{4}x^2\) 或 \(y = \frac{1}{2}x^2 + Cx + C^2\)</p>
        </div>
      </div>
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
      <div class="solution">
        <div class="solution-title">参考解答</div>
        <div class="math-content">
          <p>考虑一阶线性微分方程：\(f'(x) + f(x) = g(x)\)</p>
          <p>积分因子：\(\mu(x) = \mathrm{e}^{\int 1\mathrm{d}x} = \mathrm{e}^x\)</p>
          <p>方程化为：\((\mathrm{e}^x f(x))' = \mathrm{e}^x g(x)\)</p>
          <p>积分得：\(\mathrm{e}^x f(x) = C + \int_{-\infty}^x \mathrm{e}^t g(t)\mathrm{d}t\)</p>
          <p>由于\(f(x)\)在\(\mathbb{R}\)上有界，考虑\(x \to -\infty\)时：</p>
          <p>左边\(\mathrm{e}^x f(x) \to 0\)，右边若\(C \neq 0\)则不会趋于0，因此必须有\(C = 0\)</p>
          <p>于是：\(f(x) = \mathrm{e}^{-x} \int_{-\infty}^x \mathrm{e}^t g(t)\mathrm{d}t\)</p>
          <p>取绝对值：</p>
          <p>\[|f(x)| = \left|\mathrm{e}^{-x} \int_{-\infty}^x \mathrm{e}^t g(t)\mathrm{d}t\right| \le \mathrm{e}^{-x} \int_{-\infty}^x \mathrm{e}^t |g(t)|\mathrm{d}t\]</p>
          <p>由于\(|g(t)| \le M\)，有：</p>
          <p>\[|f(x)| \le M\mathrm{e}^{-x} \int_{-\infty}^x \mathrm{e}^t\mathrm{d}t = M\mathrm{e}^{-x} \cdot \mathrm{e}^x = M\]</p>
          <p>因此\(|f(x)| \le M\)，证毕. </p>
        </div>
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
