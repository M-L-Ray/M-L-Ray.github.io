---
title: "数学分析II - 历年考试资料"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-2
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
---

## 课程信息
**主讲教师：** 苗俊杰副教授，戴浩晖副教授  
**开课时间：** 春季学期 

<div class="exam-toc">
  <h2> 目录</h2>
  <ul>
    <li><a href="#2024-spring-test3">2024春季学期第三次小测</a></li>
    <li><a href="#2025-spring-test1">2025春季学期第一次小测</a></li>
    <li><a href="#2025-spring-test2">2025春季学期第二次小测</a></li>
    <li><a href="#2025-spring-test3">2025春季学期第三次小测</a></li>
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

<div id="2024-spring-test3" class="exam-header">
  <h3>2024春季学期第三次小测</h3>
  <div class="exam-meta">总分：100分 | 考试时间：未指定</div>
</div>

<details markdown="1">
  <summary>📝 查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 - 判断题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断3分，理由2分）</p>
        <p>1. 若非负无穷积分\(\displaystyle\int_a^{+\infty} f(x)\ \mathrm{d}x\)收敛且\(f(x)\)在\([a,+\infty)\)上连续，则\(\lim\limits_{x\to+\infty}f(x)=0.\)</p>
        <p>2. 若无穷积分\(\displaystyle\int_a^{+\infty} f(x)\ \mathrm{d}x\)绝对收敛，则无穷积分\(\displaystyle\int_a^{+\infty} f^2(x)\ \mathrm{d}x\)也收敛.</p>
        <p>3. 若正项级数\(\sum u_n\)收敛，则\(\ \exists\ N,\ n>N\)时\(\sqrt[n]{u_n}<q\)，其中\(q\in [0,1).\)</p>
        <p>4. 若对任意\( p\in \mathbb{N} _+,\ \forall \varepsilon>0,\exists\ N\in\mathbb{N} _+\)，当\(n>N\)时，\(\|u _{n+1}+u _{n+2}+\cdots +u _{n+p}\|<\varepsilon\)，则\(\sum u_n\)收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 - 反常积分敛散性</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>讨论下列反常积分的敛散性（绝对收敛、条件收敛或发散）</p>
        <p>1. \(\displaystyle\int_1^{+\infty} e^{-x}\arccos x \ \mathrm{d}x\);</p>
        <p>2. \(\displaystyle\int_0^1 \frac{\sqrt{x}}{e^{x^2}-1} \ \mathrm{d}x\);</p>
        <p>3. \(\displaystyle\int_0^1 \frac{\ln(1+\sin x)}{x^p}\ \mathrm{d}x,(p>0)\);</p>
        <p>4. \(\displaystyle\int_0^{+\infty} \frac{\cos(x^2)}{(1+x)^p} \mathrm{d}x\).</p>
      </div>
    </div>

    <!-- 继续添加其他题目，结构相同 -->
    <div class="question">
      <div class="question-title">
        <span>第3题 - 数项级数敛散性</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>讨论下列数项级数的敛散性（绝对收敛、条件收敛或发散）</p>
        <p>1. \(\displaystyle\sum \frac{(-1)^nn^3}{3^n}\);</p>
        <p>2. \(\displaystyle\sum \frac{(2n+1)!!}{(2n)^n} \);</p>
        <p>3. \(\displaystyle\sum \frac{\sin 2n}{\sqrt{n}}\);</p>
        <p>4. \(\displaystyle\sum \frac{1}{\ln((n+1)!)} \).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设函数\(f(x)\)在\([1,+\infty\)上非负递减，若\(\displaystyle\int_1^{+\infty}x^2f(x)\ \mathrm{d}x\)收敛，证明\(\lim\limits_{x\to+\infty}x^3f(x)=0.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设数列\(\{a_n\}\)单调递减收敛于0，证明\[\sum (-1)^n\sqrt[n]{a_1a_2\cdots a_n}\]收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设正项级数\(\displaystyle\sum_{n=1}^\infty a_n\)收敛，余项\(\displaystyle R_n=\sum_{k=n+1}^\infty a_k\). 证明\(\displaystyle\sum_{n=1}^\infty\frac{a_{n+1}}{\sqrt{R_n}}\)收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明Bertrand判别法：若正项级数\(\sum u_n\)满足</p>
        <p>\[\lim_{n\to\infty}\ln(n+1)\left[(n+1)\left(1-\frac{u_{n+1}}{u_n}\right)-1\right]=b,\]</p>
        <p>则当\(b>1\)时\(\sum u_n\)收敛，当\(b<1\)时\(\sum u_n\)发散.</p>
      </div>
    </div>
  </div>
</details>

<!-- 其他考试按照相同结构继续添加 -->

<div id="2025-spring-test1" class="exam-header">
  <h3>2025春季学期第一次小测</h3>
  <div class="exam-meta">总分：100分 | 考试时间：未指定</div>
</div>

<details markdown="1">
  <summary>📝 查看完整试卷内容</summary>
  <div class="exam-content">
    <!-- 2025第一次小测内容 -->
    <div class="question">
      <div class="question-title">
        <span>第1题 - 判断题</span>
        <span class="points">28分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断4分，理由3分）</p>
        <p>1. 设数列\(\{a_n\},\{b_n\}\)均有界，则\(\varliminf\limits_{n\to\infty} (a_n+b_n)=\varliminf\limits_{n\to\infty} a_n+\varliminf\limits_{n\to\infty} b_n.\)</p>
        <p>2. 若数列\(\{a_n\}\)有界，\(\varlimsup\limits_{n\to\infty}a_n>0\)，则\(\ \exists\ N\)，当\(n>N\)时，\(a_n>0.\)</p>
        <p>3. 若定义在\(\mathbb{R}\)上的连续函数\(f(x)\)是周期函数，则\(f(x)\)的原函数\(F(x)\)一定是周期函数.</p>
        <p>4. 若定义在\(\mathbb{R}\)上的连续函数\(f(x)\)是偶函数，则\(f(x)\)的原函数\(F(x)\)一定是奇函数.</p>
      </div>
    </div>
    <!-- 继续添加其他题目 -->
  </div>
</details>

<!-- 继续添加2025春季学期第二次和第三次小测 -->

<div class="download-section">
  <h2>📥 资源下载</h2>
  <p>如需下载完整试卷集合，请联系课程助教或访问课程网站。</p>
</div>

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
