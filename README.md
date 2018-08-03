个人博客 <https://ahuojun.github.io/>，fork 自大神 [Nicole White](https://nicolewhite.github.io/)，并修改自前辈大神 [Nicole White](https://tsai1993.github.io/)的中文改版。

### 优化

fork 之后，做了若干优化。

* **去除斜体**：中文没有斜体，默认去除一切斜体，包括代码注释。
* **代码块不段行**：将默认代码块自动段行改为不段行，提高移动端阅读体验。
* **更改行内代码背景颜色**：更改行内代码背景颜色，与正文相区分。
* **更改字号大小**：正文从 14px 改为 15px，引用从 17.5px 改为 14 px。
* **标题加粗**

### 使用

1. fork 本项目，在设置中将项目名称更改为 `[注册用户名].github.io`。然后更改 `_includes/main_sidebar.html` 中的简介和信息，不必要的可以注释掉。
2. 将 `_layouts/post.html` 中的链接改为你的地址。
4. 更改 `404.html` 中的网址。
3. 以 `_posts` 里的格式写文章，然后 push。
