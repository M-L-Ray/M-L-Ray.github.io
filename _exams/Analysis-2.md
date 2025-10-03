---
title: "数学分析II"
collection: exams
type: "Undergraduate course"
permalink: /exams/analysis-2
venue: "ECNU"
date: 2025-06-23
location: "Shanghai, China"
grade: 1.5
---

**主讲教师：** 苗俊杰副教授，戴浩晖副教授

<div class="exam-toc">
  <h2>考试目录</h2>
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
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
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

<div id="2025-spring-test1" class="exam-header">
  <h3>2025春季学期第一次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
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

    <div class="question">
      <div class="question-title">
        <span>第2题 - 上下极限计算</span>
        <span class="points">16分</span>
      </div>
      <div class="math-content">
        <p>求以下数列的上下极限：</p>
        <p>1. \(\left\{\dfrac{n}{n+1}2^{(-1)^n}\right\}\);</p>
        <p>2. \(\left\{\sin\dfrac{n\pi}{3}\right\}\);</p>
        <p>3. \(\left\{\sqrt[n]{n}\ln\dfrac{n+1}{n}\right\}\);</p>
        <p>4. \(\{\sin n\}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 - 不定积分计算</span>
        <span class="points">32分</span>
      </div>
      <div class="math-content">
        <p>计算以下不定积分</p>
        <p>1. \(\displaystyle \int (x+1)e^{x^2+2x+1}\ \mathrm{d}x\)；</p>
        <p>2. \(\displaystyle \int \frac{\mathrm{d}x}{\sqrt{x}+\sqrt[3]{x}}\)；</p>
        <p>3. \(\displaystyle \int \frac{ \mathrm{d}x}{2+\sin x}\)；</p>
        <p>4. \(\displaystyle \int \frac{\mathrm{d}x}{x(x+1)(x^2+2x+2)}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 - 证明题</span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>证明，若数列\(\{ a_n\}\)有界，\(\varliminf\limits_{n\to\infty} a_n>0\)，则\(\exists~N\)，当\(n>N\)时，\(a_n>0.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 - 证明题</span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>证明，若数列\(\{ a_n\}\)有界，则\(A=\varlimsup\limits_{n\to\infty}a_n\)的充要条件是\(A=\inf\limits_{n}\sup\limits_{k\ge n}\{a_k\}\).</p>
      </div>
    </div>
  </div>
</details>

<div id="2025-spring-test2" class="exam-header">
  <h3>2025春季学期第二次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 - 定积分计算</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>计算下列定积分</p>
        <p>1. \(\displaystyle \int_{-1}^4 \cos x e^{\sin x}\ \mathrm{d}x\);</p>
        <p>2. \(\displaystyle \int_{-2}^2 x\cos^4x\ \mathrm{d}x\);</p>
        <p>3. \(\displaystyle \int_0^1 \frac{\mathrm{d}x}{(1+x^2)^2}\);</p>
        <p>4. \(\displaystyle \int_2^3  x\ln x\ \mathrm{d}x\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 - 判断题</span>
        <span class="points">30分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断3分，理由2分）</p>
        <p>1. 若函数\(f(x)\)在\([a,b]\)上可积，则存在\(\xi\in[a,b]\)，使得\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x=f(\xi)(b-a).\)</p>
        <p>2. 若\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x\ge 0\)，则\(f(x)\ge 0,\forall x\in[a,b].\)</p>
        <p>3. 若函数\(f(x)\)在\([a,b]\)上可积，则\(F(x)=\displaystyle\int_a^x f(t)\ \mathrm{d}t\)可导.</p>
        <p>4. 若函数\(\|f(x)\|\)在\([a,b]\)可积，则\(f(x)\)在\([a,b]\)上可积.</p>
        <p>5. 定积分\(\displaystyle\int_{a}^bf(x)\ \mathrm{d}x\)的几何意义是由直线\(x=a,x=b,x\)轴以及曲线\(y=f(x),x\in[a,b]\)所围成的平面图形的面积.</p>
        <p>6. 若\(f(x)\)在\([a,b]\)上可积且\(f(x)\neq 0,\forall x\in[a,b]\)，则\(\dfrac{1}{f(x)}\)在\([a,b]\)上也可积.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 - 几何应用</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>1. 求第一象限中由极坐标曲线\(r=\sqrt{3}\sin \theta,r=\cos\theta\)所围成的平面图形的面积.</p>
        <p>2. 求曲线\(C:\begin{cases}x(t)=t-t^2\\y(t)=1+\dfrac{4\sqrt{2}}{3}t^{\frac{3}{2}}\end{cases},t\in[0,1]\)的弧长.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 - 积分与极限</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>1. \(\displaystyle f(x)=\int_{\arcsin x}^{\ln(x+1)}e^{-t^2}\ \mathrm{d}t,x\in\left[\frac{1}{2},1\right]\)，求\(f'(x)\);</p>
        <p>2. 求极限\(\lim\limits_{x\to 0}\dfrac{\int_{2x}^{x^2}tf(t)\ \mathrm{d}t}{x^2}\)，其中\(f\)为\(\mathbb{R}\)上的连续函数.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 - 旋转体体积</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>计算由直线\(x=4,x\)轴以及曲线段\(y=\sqrt{x},x\in[0,4]\)所围平面图形绕\(y\)轴旋转一周所得旋转体的体积.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 - 旋转曲面面积</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>计算由曲线段\(y=\sqrt{x},x\in[0,4]\)绕\(x\)轴旋转一周所得的旋转曲面的面积.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\(f\)在\([0,1]\)上连续可微，\(0\le f'(x)\le 1,\ \forall x\in[0,1],\ f(0)=0.\)，证明</p>
        <p>\[\left(\int_0^1 f(x)\ \mathrm{d}x\right)^2\ge\int_0^1[f(x)]^3\ \mathrm{d}x,\]</p>
        <p>且等号仅在\(f(x)=x\)或\(f(x)\equiv 0\)时成立.</p>
      </div>
    </div>
  </div>
</details>

<div id="2025-spring-test3" class="exam-header">
  <h3>2025春季学期第三次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>查看完整试卷内容</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 - 判断题</span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断3分，理由2分）</p>
        <p>1. 若\(f(x)\le g(x),\forall x\in[a,+\infty)\)，无穷积分\(\displaystyle\int_a^{+\infty}g(x)\ \mathrm{d}x\)收敛，则无穷积分\(\displaystyle\int_a^{+\infty}f(x)\ \mathrm{d}x\)收敛.</p>
        <p>2. 若非负无穷积分\(\displaystyle\int_a^{+\infty}f(x)\ \mathrm{d}x\)收敛，则\(\ \exists\ p>1\)，使得极限\(\lim\limits_{x\to+\infty}x^p f(x)\)存在.</p>
        <p>3. 若\(u_n>0,\forall n\)，数项级数\(\sum u_n\)收敛，则\(\ \exists\ N,\ n>N\)时\(\dfrac{u_{n+1}}{u_n}\le q\)，其中\(q\in [0,1)\).</p>
        <p>4. 若\(u_n\ge 0,\forall n\)，且\(\ \exists\ N\in\mathbb{N}_+\)，当\(n>N\)时，\(\sqrt[n]{u_n}<1\)，则\(\sum u_n\)收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 - 反常积分计算</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>计算下列反常积分的值：</p>
        <p>1. \(\displaystyle \int_1^{+\infty}e^{-x}\cos x\ \mathrm{d}x\);</p>
        <p>2. \(\displaystyle\int_0^2\frac{1}{x^{\frac{2}{3}}}\ \mathrm{d}x\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 - 数项级数求和</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>计算下列数项级数的和：</p>
        <p>1. \(\displaystyle\sum_{n=1}^\infty\frac{2+(-1)^n}{4^n}\);</p>
        <p>2. \(\displaystyle\sum_{n=1}^\infty\frac{n}{(n+1)(n+2)(n+3)}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 - 反常积分敛散性</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>讨论下列反常积分的敛散性：</p>
        <p>1. \(\displaystyle\int_1^{+\infty}\frac{x^2}{2^x}\ \mathrm{d}x\);</p>
        <p>2. \(\displaystyle\int_0^1\frac{\arctan x}{\sqrt{x}\ln(1+x)}\ \mathrm{d}x\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 - 数项级数敛散性</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>讨论下列数项级数的敛散性：</p>
        <p>1. \(\displaystyle\sum_{n=1}^\infty\frac{1}{2^{\ln n}}\);</p>
        <p>2. \(\displaystyle\sum_{n=2}^\infty\frac{1}{\sqrt{n}+(-1)^n}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明瑕积分\(\displaystyle\int_0^1\frac{\ln x}{x^p}\ \mathrm{d}x\)当\(0<p<1\)时收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明数项级数\(\displaystyle\frac{(-1)^n\sin n}{n}\)条件收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第8题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明反常积分</p>
        <p>\[\int_0^{+\infty}\frac{\sin x}{(x-\ln x)^p}\ \mathrm{d}x\]</p>
        <p>当\(p>1\)时绝对收敛，当\(0<p\le 1\)时条件收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第9题 - 证明题</span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\(\{a_n\}\)为单调递增无界的数列，且\(a_1>0\)，令</p>
        <p>\[u_n=\frac{a_{n+1}-a_n}{a_n^pa_{n+1}}.\]</p>
        <p>证明：当\(p>0\)时，级数\(\sum u_n\)收敛.</p>
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
