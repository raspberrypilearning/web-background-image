你可以添加背景图片以显示在网页上其他元素的后面。

![网页主要内容后面的彩色电子电路背景。](images/background-image.png)

在 `style.css` 中找到此样式声明：

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

/*向 body 添加背景图片 */

body {
  /*background-image: url('name.jpg');*/ /* 取消注释并更改文件名以添加背景图片 */
  /*background-repeat: repeat;*/ /* 使图片重复 */
  /*background-size: cover;*/ /* 使图片覆盖整个容器 */
}

--- /code ---

删除 `/*` 和 `*/` 注释标记并将 `name.jpg` 替换为背景图像的名称。

--- code ---
---
language: CSS
filename: style.css
line_numbers: false
---

/*向 body 添加背景图片 */

body {
  background-image: url('mybackground.png'); /* 取消注释并更改文件名以添加背景图片 */
  /*background-repeat: repeat;*/ /* 使图片重复 */
  /*background-size: cover;*/ /* 使图片覆盖整个容器 */
}

--- /code ---

你也可以尝试取消注释其他属性。

**提示：**你不需要更新 HTML，因为此样式直接应用于 `<body>` 标签。 你可以创建一个类来将背景图片应用于特定元素。


