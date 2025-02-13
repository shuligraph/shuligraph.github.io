---
layout: none
---

# LaTeX 备忘录

<style>
.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  padding: 10px;
}

.grid-container div {
  padding: 10px;
  border: 1px solid #ddd;
}
</style>

<div class="grid-container">
  <div>
    <h2>LaTeX 命令</h2>
    <ul>
      <li><code>\textbf{加粗}</code>：加粗文本</li>
      <li><code>\textit{斜体}</code>：斜体文本</li>
      <li><code>\underline{下划线}</code>：下划线</li>
      <li>行内公式：`$E=mc^2$`</li>
      <li>块级公式：</li>
    </ul>
    <pre>
    $begin:math:display$
    \\begin{bmatrix} 1 & 2 \\\\ 2 & 2 \\end{bmatrix}
    $end:math:display$
    </pre>
  </div>
  <div>
    <h2>作用</h2>
    <ul>
      <li>加粗文本</li>
      <li>斜体文本</li>
      <li>下划线</li>
      <li>行内公式：`$E=mc^2$`</li>
      <li>块级公式：矩阵显示</li>
    </ul>
  </div>
</div>
