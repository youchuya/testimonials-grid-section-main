# Testimonials grid section

Frontend Mentor 挑战（Junior），纯 HTML + CSS，无框架、无 JS。

- [Live site](https://youchuya.github.io/testimonials-grid-section/)
- [Challenge](https://www.frontendmentor.io/challenges)

## 学到什么

- CSS Grid：`repeat(4, 1fr)` + `grid-column` / `grid-row` 做跨列跨行
- 布局策略：DOM 顺序按手机稿排，桌面端用 grid 显式摆位
- 响应式：`@media (max-width: 900px)` 单列，并清掉桌面的 grid 定位
- 文字层级：深色卡「白字 + opacity」，白卡「灰字」
- 本地字体：Barlow Semi Condensed 500 / 600，`@font-face` 引入
- 装饰图：SVG 作为 `background-image`，位置用 `background-position` 调

## 设计还原

尺寸、字号、间距均从 JPG 设计稿反推；卡片宽 540 / 255，容器 1110，gap 30。
