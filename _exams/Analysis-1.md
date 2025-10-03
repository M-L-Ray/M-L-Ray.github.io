---
title: "数学分析I"
collection: exams
type: "专业必修课程"
permalink: /exams/analysis-1
venue: "ECNU"
date: 2025-01-13
location: "Shanghai, China"
grade: 1.0
a: 大一上
instructor: 苗俊杰副教授，戴浩晖副教授，王丽萍教授，赵纯奕教授
---

<div class="exam-toc">
  <h2>考试目录</h2>
  <ul>
    <li><a href="#2023-fall-test1">2023秋季学期第一次小测</a></li>
    <li><a href="#2023-fall-test2">2023秋季学期第二次小测</a></li>
    <li><a href="#2024-fall-test2">2024秋季学期第二次小测</a></li>
    <li><a href="#2024-fall-final">2024秋季学期期末考试</a></li>
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

<div id="2023-fall-test1" class="exam-header">
  <h3>2023秋季学期第一次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断2分，理由3分）</p>
        <p>1. 给定数列\(\{a_n\}\)和实数\(a\)，若对任意\(\varepsilon>0\)，在\(U(a,\varepsilon)\)中总包含\(\{a_n\}\)中的无穷多项，则数列\(\{a_n\}\)以\(a\)为极限；</p>
        <p>2. \(f(x)=\max\{\|x\|,e^x\},x\in\mathbb{R}\)是一个初等函数；</p>
        <p>3. 给定数列\(\{a_n\}\)，若对任意\(\varepsilon>0\)，存在\(N>0\)使得对\(n>N\)都有\(\|a_n-a_{2n}\|<\varepsilon\)，则数列\(\{a_n\}\)收敛；</p>
        <p>4. 存在一个数列\(\{a_n\}\)，对任意\(a\in[0,1]\)，都存在一个子列\(\{a_{n_{k}}\}\)使得\(\lim\limits_{k\to +\infty}a_{n_{k}}=a.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>写出下确界的定义，并对给定的非空有界集合\(A\)与\(B\)，证明\(\inf(A\cup B)=\min\{\inf A,\inf B\}.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>给定数列\(\{a_n\}\)和实数\(a\)，若对任意\(k\in\mathbb{N}_+\)，存在\(N>0\)，使得对任意\(n>N\)，都有\(\|a_n-a\|<\dfrac{1}{10^k}\). 证明\(\lim\limits_{n\to+\infty}a_n=a.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>写出数列极限的\(\varepsilon-N\)定义，并用其证明\(\lim\limits_{n\to+\infty}\dfrac{6n^2+7}{4n^2+4n+1}=\dfrac{3}{2}.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明数集\(\{x\in\mathbb{Q}:x^2\le 2\}\)没有最大元.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>写出非正常极限\(\lim\limits_{n\to+\infty}a_n=\infty\)的定义，并用其证明\(\lim\limits_{n\to+\infty} (-n)^n=\infty\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\[a_n=\sqrt{1+\sqrt{2+\cdots+\sqrt{n}}}\]证明\(\{a_n\}\)收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第8题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设\(x_1=a>0,x_{n+1}=10\sqrt{x_n},n=1,2,\cdots\)，求数列\(\{x_n\}\)的极限.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第9题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>叙述数列收敛的柯西准则，并用其证明\(\{\sin n\}\)不收敛.</p>
      </div>
    </div>
  </div>
</details>

<div id="2023-fall-test2" class="exam-header">
  <h3>2023秋季学期第二次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由（判断2分，理由3分）</p>
        <p>1. 若\(\lim\limits_{x\to+\infty}f(x)\)和\(\lim\limits_{x\to+\infty}f(x)g(x)\)都存在，则\(g(x)\)在\(+\infty\)存在极限；</p>
        <p>2. 若函数\(f\)、\(f-g\)在\(x_0\)处都连续，则\(g\)在\(x_0\)处也连续；</p>
        <p>3. 区间\((a,b)\)上的连续函数\(f(x)\)在区间\((a,b)\)上必定一致连续；</p>
        <p>4. 设\(f(x),g(x)\)均为\(x\to x_0\)时的无穷小量且\(f(x)=O(g(x)),x\to x_0\)，若\(f(x)\)不是\(g(x)\)的同阶量，那么\(f(x)\)必定是\(g(x)\)的高阶无穷小量.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题  </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>写出极限\(\lim\limits_{x\to x_0^+}f(x)=A\)的\(\varepsilon-\delta\)定义，并用其证明\(\lim\limits_{x\to 1^+}\dfrac{x^3+1}{x}=2.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题  </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>叙述极限\(\lim\limits_{x\to x_0^-}f(x)=A\)的柯西收敛准则并用其证明\(\lim\limits_{x\to 0^-}\cos\frac{1}{x^2}\)不存在.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>设函数\( f\)在\(x_0\)处连续，证明\(\forall \alpha>f(x_0),\exists\ \delta>0\)，当\(\|x-x_0\|<\delta\)时，\(f(x)<a\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题  </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>给出函数\(f\)在区间\(I\)上不一致收敛的充要条件，并用其验证\(y=\sin x^2\)在\([0,+\infty)\)上不一致收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">12分</span>
      </div>
      <div class="math-content">
        <p>证明：</p>
        <p>1. \(\sqrt{x+\sqrt{x+\sqrt{x}}}\sim \sqrt[8]{x},x\to 0,\)</p>
        <p>2. \(\sqrt{x+\sqrt{x+\sqrt{x}}}\sim \sqrt{x},x\to +\infty.\)</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>证明\(\lim\limits_{x\to -\infty}f(x)=\infty\)的充要条件是：对任意单调减且趋于\(-\infty\)的数列\(\{x_n\}\)都有\(\lim\limits_{n\to \infty}f(x_n)=\infty\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第8题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>\(f(x)\)定义在\([a,b]\)上，对每一点\(x_0\in[a,b]\)满足：\(\forall \varepsilon,\ \exists\ \delta>0\)，当\(x\in(x_0-\delta,x_0+\delta)\cap[a,b] \)时\(f(x)>f(x_0)-\varepsilon\). 证明：\(f(x)\)在\([a,b]\)上能取得最小值.</p>
      </div>
    </div>
  </div>
</details>

<div id="2024-fall-test2" class="exam-header">
  <h3>2024秋季学期第二次小测</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">30分</span>
      </div>
      <div class="math-content">
        <p>判断下列陈述是否正确，并简述理由</p>
        <p>1. 设 \( A \in \mathbb{R} \), 且 \( \forall n \in \mathbb{N} \), 存在 \( \delta > 0 \), 当 \( 0 < \|x - x_0\| < \delta \) 时成立 \( \|f(x) - A\| < \dfrac{1}{n} \), 则 \( \lim\limits_{x \to x_0} f(x) = A \).</p>
        <p>2. 若 \( f(x) \) 在 \( x_0 \) 的某空心邻域内有定义且 \( \lim\limits_{x \to x_0} \|f(x)\| \) 存在，则 \( \lim\limits_{x \to x_0} f(x) \) 也存在.</p>
        <p>3. 若存在正数 \( \varepsilon_0 \) 和两个数列 \( \{x_n\} \), \( \{y_n\} \) 满足 \( x_n \to x_0 \), \( y_n \to x_0 \), 且 \( \forall n \in \mathbb{N}_ + \), \( \|f(x_n) - f(y_n)\| \geq \varepsilon_0 \), 则 \( \lim\limits_{x \to x_0} f(x) \) 不存在.</p>
        <p>4. 若 \( f(x) \) 在点 \( x_0 \) 的某空心邻域内单调有界，则 \( f(x) \) 在点 \( x_0 \) 处的极限存在.</p>
        <p>5. 设 \( f(x) \) 定义在 \( (1,+\infty) \) 上，且当 \( x \to +\infty \) 时 \( f(x) \) 不是无穷大量，则存在数列 \( \{x_n\} \subset (1,+\infty) \), 使得 \( x_n \to +\infty \) 且数列 \( \{f(x_n)\} \) 有界.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">30分</span>
      </div>
      <div class="math-content">
        <p>计算题</p>
        <p>1. 求极限 \( \lim\limits_{x \to +\infty} (\sqrt{x+1} - \sqrt{x}) \cos x \).</p>
        <p>2. 求极限 \( \lim\limits_{x \to 0} \dfrac{\tan x - \sin x}{x^2 \sin 2x} \).</p>
        <p>3. 求极限 \( \lim\limits_{x \to 0} \left( \dfrac{1+2x}{1-x} \right)^{\cot x} \).</p>
        <p>4. 求极限 \( \lim\limits_{x \to +\infty} \left( \dfrac{[x]}{x} + \left[ \dfrac{1}{x} \right] \right) \), 其中 \( [ \cdot ] \) 表示向下取整.</p>
        <p>5. 求函数 \( f(x) = \dfrac{x^3 + 2}{x^2(x-1)} \) 的渐近线.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>判断函数 \( f(x) = \dfrac{\sin x}{x^2} + \dfrac{x+2}{(x^2-4)(x+1)} \) 的间断点，并指明其类型.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设函数 \( f(x) \) 在 \( [a,b] \) 上有定义，\( \forall x \in (a,b) \), 且 \( \forall x,y \in [a,b] \), \( x \neq y \) 时有 \( \|f(x) - f(y)\| < \|x - y\| \). 证明：存在唯一的点 \( \xi \in [a,b] \), 使得 \( f(\xi) = \xi \).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设函数 \( f(x) \) 定义在 \( \mathbb{R} \) 上，且在 \( x = 0 \) 处连续. 若存在 \( a \in (0,1) \) 满足 \( \forall x \in \mathbb{R} \) 有 \( f(ax) = f(x) \), 证明：\( f(x) = f(0) \), \( \forall x \in \mathbb{R} \).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>设 \( f(x) \) 在 \( U^o(0,1) \) 上有定义，满足 \( \lim\limits_{x \to 0} f(x) = 0 \) 且 \( f(x) - f\left(\dfrac{x}{2}\right) = o(x) \) (\( x \to 0 \)). 证明：\( f(x) = o(x) \) (\( x \to 0 \)).</p>
      </div>
    </div>
  </div>
</details>

<div id="2024-fall-final" class="exam-header">
  <h3>2024秋季学期期末考试</h3>
  <div class="exam-meta">总分：100分</div>
</div>

<details markdown="1">
  <summary>完整试题</summary>
  <div class="exam-content">
    <div class="question">
      <div class="question-title">
        <span>第1题 </span>
        <span class="points">16分</span>
      </div>
      <div class="math-content">
        <p>判断下列命题是否正确并给出理由（每题4分）</p>
        <p>1. 若\(\forall n \in \mathbb{N}^+\)，\(\exists \delta > 0\)，\(\forall x \in (x_0 - \delta, x_0) \cup (x_0, x_0 + \delta)\)，\(\|f(x) - A\| < \dfrac{1}{\sqrt{n}}\)，则 \(\lim\limits_{x \to x_0} f(x) = A\).</p>
        <p>2. 任意数列必有收敛子列.</p>
        <p>3. 若 \(f(x)\) 在 \((a, b]\) 上一致连续，则 \(\lim\limits_{x \to a^+} f(x)\) 存在.</p>
        <p>4. 设 \(D(x)\) 为 Dirichlet 函数，则存在函数 \(F(x)\)，使得 \(F'(x) = D(x)\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第2题 </span>
        <span class="points">20分</span>
      </div>
      <div class="math-content">
        <p>计算下列极限或导数</p>
        <p>1. 求 \(\lim\limits_{n \to \infty} \left( 1 + \dfrac{1}{2n+1} \right)^n\).</p>
        <p>2. 求 \(\lim\limits_{x \to 0} \dfrac{(1+x)^{\frac{1}{3}}-1}{\ln(1+x)}\).</p>
        <p>3. 求 \(\lim\limits_{x \to 0} \left( \dfrac{1}{\sin^2 x} - \dfrac{1}{x^2} \right)\).</p>
        <p>4. 计算 \(f'(x)\)，其中 \(\displaystyle f(x) = \begin{cases} x^2 \cos \frac{1}{x} & x \neq 0 \\ 0 & x = 0 \end{cases}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第3题 </span>
        <span class="points">6分</span>
      </div>
      <div class="math-content">
        <p>证明： \(\tan x + \sin x > 2x\)， \(\forall x \in \left(0, \dfrac{\pi}{2}\right)\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第4题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>研究 \(\displaystyle f(x) = \frac{(\ln x)^2}{x}\) 有哪些极值？若是最值也请指出.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第5题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>设 \(\displaystyle a_n = \sin 1 + \frac{\sin 2}{2^2} + \cdots + \frac{\sin n}{n^2}\)，证明： \(\{a_n\}\) 收敛.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第6题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>设 \(f\) 是在开区间 \(I\) 上的凸函数， \(g\) 是在开区间 \(J\) 上的严格单增凸函数， \(f(I) \subset J\)，若 \(g \circ f\) 在 \(I\) 上存在最大值，证明： \(f\) 是常值函数.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第7题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>设 \(f(x)\) 在 \([a, b]\) 上一阶连续可导，在 \((a, b)\) 上二阶可导且存在一个极值点，证明：存在 \(\xi \in (a, b)\)，使得 \(\displaystyle \|f(b) - f(a)\| \leq \frac{(b-a)^2}{2} \|f''(\xi)\|\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第8题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>设 \(f(x)\) 是定义在 \((-\infty, +\infty)\) 上的连续函数，且 \(\displaystyle \lim\limits_{x \to \infty} f(x) = A\)，证明： \(f(x)\) 必在 \((-\infty, +\infty)\) 上存在最值.</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第9题 </span>
        <span class="points">8分</span>
      </div>
      <div class="math-content">
        <p>设 \(f(x)\) 在 \([a, b]\) 上连续，在 \((a, b)\) 上可导，且 \(f(x)\) 不是线性函数，证明：存在 \(\xi_1, \xi_2 \in (a, b)\)，使得 \(\displaystyle f'(\xi_1) > \frac{f(b)-f(a)}{b-a}\), \(\displaystyle f'(\xi_2) < \frac{f(b)-f(a)}{b-a}\).</p>
      </div>
    </div>

    <div class="question">
      <div class="question-title">
        <span>第10题 </span>
        <span class="points">10分</span>
      </div>
      <div class="math-content">
        <p>用有限覆盖定理证明聚点定理.</p>
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
