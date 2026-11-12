# AIME + LLM 新闻分类互动演示

一个用于课堂展示的单页演示：点击新闻标题，机器用「词袋（0/1）」把它向量化，再和每个话题的 AIME 特征词比对，逐步展示归类过程。

- 纯前端、无需后端、无需联网
- 数据：NewsAPI 免费档 493 篇美国政治新闻
- 方法：TF-IDF/词袋 + k-means + AIME（aime-xai）+ LLM 命名

对应论文：*Interpretable News Clustering and Topic Attribution for the U.S. Presidential Election: An AIME and LLM Approach*（IEEE SERA 2025）

## 本地使用
直接双击 `index.html` 即可，或部署到任意静态托管（GitHub Pages 等）。
