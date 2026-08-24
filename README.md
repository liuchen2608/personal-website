# 个人主页 / Portfolio

一个现代、编辑风格的响应式个人作品集页面。深色克制、暖纸质感，用于面试展示与技术实践。

## ✨ 特性

- **编辑式设计系统**：暖纸白 + 石墨黑，仅以 Ember 橙 `#ff682c` 作功能性点缀；Space Grotesk 400 标题、无阴影、不对称圆角
- **GitHub 实时数据**：通过 GitHub API 拉取真实仓库（星级 / 语言 / fork），失败自动降级演示数据
- **克制型交互**：滚动进度条、数字滚动、折线图描线入场、技能环进度动画、打字机效果
- **项目筛选**：按类型（Web 应用 / 开源工具 / 移动端 / 设计系统）过滤项目
- **全流程管线**：可交互的「从设计到上线」五阶段流程展示（点击 / 键盘切换）
- **响应式**：桌面与移动端自适应

## 🛠 技术栈

- 原生 HTML / CSS / JavaScript（零依赖，单文件）
- IntersectionObserver 滚动动画
- SVG 数据可视化
- GitHub REST API

## 🚀 本地运行

直接双击 `index.html`，或用任意静态服务器：

```bash
python3 -m http.server 8000
```

然后访问 http://localhost:8000

## ⚙️ 自定义

在 `index.html` 底部 `<script>` 开头修改 GitHub 用户名以显示真实仓库：

```js
const GITHUB_USERNAME = '你的用户名';
```

## 📄 License

MIT
