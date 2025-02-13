---
layout: none
---

# LaTeX 备忘录

<script type="text/javascript" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>

<style>
  /* 设置整体字体 */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

/* 设置有序列表的样式 */
ol {
  font-size: 16px;
  padding-left: 20px;
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 这里确保每一列宽度相等 */
  gap: 20px; /* 设置栏间距 */
  margin: 0;
}

ol li {
  margin-bottom: 15px;
}

ol li h3 {
  font-size: 18px; /* 统一标题和编号的大小 */
  font-weight: bold;
  margin-top: 0;
}

/* 针对内容的布局，显示命令和输出 */
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr; /* 这里确保每一栏的宽度相等 */
  gap: 10px;
  margin: 0;
}

.grid-container div {
  padding: 5px;
  border: 1px solid #ddd;
}

.grid-container code {
  display: block;
  background-color: #f4f4f4;
  padding: 5px;
  border-radius: 5px;
  font-size: 14px;
  white-space: nowrap;
}

/* 针对矩阵命令的特殊样式，保证框宽 */
.matrix-code {
  display: block;
  background-color: #f9f9f9;
  padding: 10px;
  border: 2px solid #ddd;
  border-radius: 5px;
  font-size: 14px;
  white-space: nowrap;
}

/* 处理条目的分栏，添加换列逻辑 */
@media screen and (max-width: 768px) {
  ol {
    grid-template-columns: repeat(2, 1fr); /* 小屏设备，2列布局 */
  }
}

@media screen and (max-width: 500px) {
  ol {
    grid-template-columns: 1fr; /* 更小的屏幕，单列布局 */
  }
}
</style>

<ol>
  <li>
    <h3>测试1</h3>
    <div class="grid-container">$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
$ \sqrt{5} $ : \verb|\sqrt{5}
    </div>
  </li>
  <li>
    <h3>测试</h3>
    <div class="grid-container">
      <div class="command">123</div>
      <div class="output">456</div>
    </div>
  </li>
  <li>
    <h3>上标与下标</h3>
    <div class="grid-container">
      <div class="command"><code>\textbf{上标} \q \verb|^| \quad \textbf{下标} \q \verb|_|</code></div>
      <div class="output">$ A_b^c $ : \verb|A_b^c| <br> $ A_{bc}^{def} $ : \verb|A_{bc}^{def}|</div>
    </div>
  </li>

  <li>
    <h3>分数与根号</h3>
    <div class="grid-container">
      <div class="command"><code>\frac{分子}{分母}</code></div>
      <div class="output">$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}| <br> $ \sqrt{5} $ : \verb|\sqrt{5}|</div>
    </div>
  </li>

  <li>
    <h3>运算符</h3>
    <div class="grid-container">
      <div class="command"><code>+</code></div>
      <div class="output">$ + $ : \verb|+|</div>
    </div>
    <div class="grid-container">
      <div class="command"><code>\odot</code></div>
      <div class="output">$ \odot $ : \verb|\odot,\bigodot|</div>
    </div>
  </li>

  <li>
    <h3>矩阵（带框）</h3>
    <div class="grid-container">
      <div class="command matrix-code"><code>\begin{bmatrix} 1 & 2 \\ 2 & 2 \end{bmatrix}</code></div>
      <div class="output">$ \begin{bmatrix} 1 & 2 \\ 2 & 2 \end{bmatrix} $ : \verb|\begin{bmatrix} 1 & 2 \\ 2 & 2 \end{bmatrix}|</div>
    </div>
  </li>

  <li>
    <h3>特殊符号（转义）</h3>
    <div class="grid-container">
      <div class="command"><code>\$</code></div>
      <div class="output">$ \$ $ : \verb|\$|</div>
    </div>
    <div class="grid-container">
      <div class="command"><code>\#</code></div>
      <div class="output">$ \# $ : \verb|\#|</div>
    </div>
  </li>

  <li>
    <h3>其它符号与形状</h3>
    <div class="grid-container">
      <div class="command"><code>\exists</code></div>
      <div class="output">$ \exists $ : \verb|\exists|</div>
    </div>
    <div class="grid-container">
      <div class="command"><code>\forall</code></div>
      <div class="output">$ \forall $ : \verb|\forall|</div>
    </div>
  </li>

  <!-- 额外的一条 -->
  <li>
    <h3>极限、连加、积分</h3>
    <div class="grid-container">
      <div class="command"><code>\lim_{n\to\infty}</code></div>
      <div class="output">$ \lim_{n\to\infty} $ : \verb|\lim_{n\to\infty}|</div>
    </div>
  </li>
</ol>
