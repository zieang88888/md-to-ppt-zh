# 🎬 Markdown PPT · 一键把 Markdown 变成幻灯片

> 写技术分享、项目汇报，再也不用手动排版了！纯前端、免费开源、打开即用。

<div align="center">

![demo](https://img.shields.io/badge/工具-在线版-blue)
![free](https://img.shields.io/badge/免费-开源-brightgreen)
![pure](https://img.shields.io/badge/纯前端-无需服务器-orange)

</div>

## ✨ 这是什么？

一个**用 Markdown 写 PPT** 的在线工具：

- 左边写 Markdown，右边实时预览幻灯片
- 一个 `---` 就是一页，自动分页
- 标题、列表、代码块、引用自动排版
- 深色/浅色主题一键切换
- 全屏放映 + 一键导出 PDF

**对标 Slidev / Marp，但更轻**：不用装 Node、不用配环境，浏览器打开就用。

## 🚀 在线使用（打开即用）

**https://zieang88888.github.io/md-to-ppt-zh/**

## 🖥️ 本地使用

```bash
git clone https://github.com/zieang88888/md-to-ppt-zh.git
cd md-to-ppt-zh
# 直接双击 index.html 即可
```

## 📖 怎么用？

### 1. 写 Markdown

```markdown
# 页面标题

- 要点一
- 要点二

---

## 第二页

> 一个引用强调
```

### 2. 分页

用 `---`（三个短横线）分页，每个段落自动变成一页幻灯片。

### 3. 放映 & 导出

- 点「▶ 放映」全屏展示
- 键盘 ← → 翻页
- 点「导出 PDF」直接打印保存

## 🎨 支持的语法

| 语法 | 效果 |
|---|---|
| `#` / `##` / `###` | 标题（自动放大为页面主题） |
| `-` / `1.` | 列表 |
| 反引号代码块 | 代码高亮卡片 |
| `> 引用` | 强调块 |
| 表格 | 自动排版 |
| `---` | 分页 |

## 🛠️ 技术栈

- 纯 HTML + CSS + JavaScript（单文件，无构建）
- [marked.js](https://github.com/markedjs/marked) 解析 Markdown
- 打印 CSS 实现 PDF 导出

## 📄 License

MIT License —— 完全免费，随意使用。

## ⭐ 支持一下

如果这个工具帮到了你，**点个 Star ⭐**！

**关注我（韩开心）**，还有 50+ 个中文开源仓库等你探索：Redis 面试、Go 面试、Java 面试、代码截图工具……持续更新中！