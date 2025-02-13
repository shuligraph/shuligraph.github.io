---
layout: non
---


<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

## LaTeX-Memo


<style>
/* 设置整体字体 */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

/* 设置有序列表的样式 */
ol {
  font-size: 16px;
  padding-left: 0;  /* 去掉默认的左边距 */
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); /* 自动换行，最小宽度200px，自动扩展 */
  gap: 20px;  /* 设置列间距和行间距 */
  margin: 0;
  /*align-items: start;  行对齐：确保所有的 <li> 项目在每行的顶部对齐 */
}

/* 列表项 */
ol li {
  margin-bottom: 15px;
}

/* 列表项标题 */
ol li h3 {
  font-size: 18px; /* 统一标题和编号的大小 */
  font-weight: bold;
  margin-top: 0;
}
</style>

<ol>
<li>
  <h3>测试1</h3>
  <div>$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
  $ \sqrt{5} $ : \verb|\sqrt{5}
  </div>
</li>

<li>
  <h3>测试1</h3>
  <div>$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
  $ \sqrt{5} $ : \verb|\sqrt{5}
  </div>
</li>

<li>
  <h3>测试1</h3>
  <div>$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
  $ \sqrt{5} $ : \verb|\sqrt{5}
  </div>
</li>

<li>
  <h3>测试1</h3>
  <div>$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
  $ \sqrt{5} $ : \verb|\sqrt{5}
  </div>
</li>

<li>
  <h3>测试1</h3>
  <div>$ \frac{\pi^2}{6} $ : \verb|\frac{\pi^2}{6}|
  $ \sqrt{5} $ : \verb|\sqrt{5}
  </div>
</li>

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

<li>
  <h3>极限、连加、积分</h3>
  <div class="grid-container">
    <div class="command"><code>\lim_{n\to\infty}</code></div>
    <div class="output">$ \lim_{n\to\infty} $ : \verb|\lim_{n\to\infty}|</div>
  </div>
</li>


<div style="display: flex; flex-wrap: wrap; gap: 20px; margin: 20px 0;">
  <div style="background-color: #000000; border-radius: 10px; padding: 15px; flex: 1 1 23%; display: flex; flex-direction: column; justify-content: space-between;">
  <div style="font-size: 16px; color: #ADD8E6; font-weight: bold;">Poster</div>
  <div style="font-size: 12px;">
      <a href="https://www.animateyour.science/post/how-to-design-an-award-winning-conference-poster" style="text-decoration: none;">Design1</a><br>
      <a href="https://www.overleaf.com/learn/latex/Posters" style="text-decoration: none;">Guide of Overleaf</a>
  </div>
</div>

<div style="background-color: #000000; border-radius: 10px; padding: 15px; flex: 1 1 23%; display: flex; flex-direction: column; justify-content: space-between;">
  <div style="font-size: 16px; color: #ADD8E6; font-weight: bold;">Beamer</div>
  <div style="font-size: 12px;">
    <a href="https://mpetroff.net/files/beamer-theme-matrix/" style="text-decoration: none;">Theme Matrix</a><br>
    <a href="https://latex-beamer.com/" style="text-decoration: none;">Design1</a><br>
    <a href="https://shootingwang.github.io/LaTeX-Beamer.html" style="text-decoration: none;">Design2</a><br>
    <a href="https://arch-blog.kidozh.com/categories/LaTeX/" style="text-decoration: none;">Design3</a><br>
    <a href="https://www.overleaf.com/learn/latex/Beamer" style="text-decoration: none;">Guide of Overleaf</a>
  </div>
</div>

<div style="background-color: #000000; border-radius: 10px; padding: 15px; flex: 1 1 23%; display: flex; flex-direction: column; justify-content: space-between;">
  <div style="font-size: 16px; color: #ADD8E6; font-weight: bold;">Tikz</div>
  <div style="font-size: 12px;">
    <a href="https://ctan.math.washington.edu/tex-archive/graphics/pgf/contrib/tikz-cd/tikz-cd-doc.pdf" style="text-decoration: none;">Tikzcd Flow</a>
  </div>
</div>






# LaTeX 备忘录



