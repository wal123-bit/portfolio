# 个人作品集网站

一个简洁优雅的个人作品集单页网站，采用原生 HTML / CSS / JavaScript 开发，无任何框架与第三方 UI 组件库。

## 技术栈

- HTML5（语义化标签、SVG 内联图标）
- CSS3（CSS 变量主题、Flexbox / Grid 布局、动画）
- 原生 JavaScript（ES6+，IntersectionObserver、localStorage）
- Google Fonts（Inter / Noto Sans SC）

## 运行方式

无需安装依赖，直接用浏览器打开 `index.html` 即可；或启动任意静态服务器：

```bash
# 以 Python 为例
python -m http.server 8080
# 然后访问 http://localhost:8080
```

## 主要功能

- **深色 / 浅色主题切换**：一键切换，主题偏好通过 localStorage 持久化
- **导航栏**：滚动时自动变化样式，并高亮当前所在区域；移动端提供汉堡菜单
- **首屏打字机效果**：循环展示多个职业身份
- **滚动动画**：区块显现、技能进度条填充、数字计数，均基于 IntersectionObserver 触发
- **作品分类筛选**：按「全部 / 网站 / 应用 / 设计」快速过滤作品卡片
- **联系表单**：带提交状态反馈的模拟发送
- **响应式设计**：适配桌面端与移动端（968px / 680px 两档断点）

## 项目结构

```
lab4/
├── index.html   # 页面结构
├── style.css    # 样式与主题
└── script.js    # 交互逻辑
```
