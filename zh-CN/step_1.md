使用 `transparent` 类使元素部分透明，以便你可以看到其背后的内容。

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<div class="transparent">
    <p>在此处添加文本</p>
</div>

--- /code ---

**提示**：调整 `style.css` 中 `transparent` 类的 `opacity` 值：`0` 表示完全透明，`1` 表示完全不透明。

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---
/*添加透明效果 */

.transparent {
  opacity: 0.95;
}
--- /code ---
