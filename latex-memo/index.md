---
layout: none
---

# LaTeX 备忘录

<style>
.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr; /* 左侧1列，右侧2列，更宽 */
  gap: 10px;  /* 列与列之间的间隔 */
  padding: 10px;
  margin: 0;
}

.grid-container div {
  padding: 5px;
  border: 1px solid #ddd;
}

.grid-container h3 {
  margin-top: 0;  /* 去掉标题与顶部的空隙 */
  font-size: 16px;
  font-weight: bold;
}

.grid-container code {
  display: block;
  background-color: #f4f4f4;
  padding: 5px;
  border-radius: 5px;
  font-size: 14px;
  white-space: nowrap;
}
</style>

<div class="grid-container">
  <!-- LaTeX 命令部分 -->
  <div>
    <h3>LaTeX 命令</h3>
    <ol>
      <li><code>\textbf{加粗}</code></li>
      <li><code>\textit{斜体}</code></li>
      <li><code>\underline{下划线}</code></li>
      <li><code>$E=mc^2$</code></li>
      <li><code>\begin{bmatrix} 1 & 2 \\ 2 & 2 \end{bmatrix}</code></li>
    </ol>
  </div>

  <!-- 输出效果部分 -->
  <div>
    <h3>输出效果</h3>
    <ol>
      <li>**加粗**：`<b>加粗</b>`</li>
      <li>*斜体*：`<i>斜体</i>`</li>
      <li><u>下划线</u>：`<u>下划线</u>`</li>
      <li>行内公式：$E=mc^2$</li>
      <li>矩阵：
        \[
        \begin{bmatrix} 
        1 & 2 \\ 
        2 & 2 
        \end{bmatrix}
        \]
      </li>
    </ol>
  </div>
</div>
