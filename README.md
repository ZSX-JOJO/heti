# 赫蹏

赫蹏（hètí）是专为中文内容展示设计的排版样式增强。它基于通行的中文排版规范而来，可以为网站的读者带来更好的文章阅读体验。

预览：[https://sivan.github.io/heti/](https://sivan.github.io/heti/)

主要特性：
- 全标签样式统一；
- 贴合网格的排版；
- 预置简体/繁体中文多种预设字体族（仅限桌面端）；
- 预置横排、直排（竖排）样式；
- 预置古文、诗词样式；
- 预置行间注排版样式；
- 预置多栏排版样式；
- 兼容 *normalize.css*、*CSS Reset* 等常见样式重置；
- 移动端支持；
- 基于 BEM；
- ……

总之，用上就会变好看。

## 使用方法

1. 在页面的 `<head>` 标签中引入 `heti.css` 文件：
    ```
    <link rel="stylesheet" href="./dist/heti.min.css">
    ```
1. 在要作用的容器元素上增加 `class="heti"` 的类名即可：。
    ```
    <article class="entry heti">
      <h1>我的世界观</h1>
      <p>有钱人的生活就是这么朴实无华，且枯燥</p>
      ……
    </article>
    ```


## WIP

- [ ] 中、西文混排
- [ ] 标点挤压
- [ ] 标点悬挂
- [x] 繁体中文支持
- [x] 诗词版式
- [x] 行间注版式

-- EOF --
