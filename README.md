# Clawlike 主题

[English](README.en.md)

Clawlike Theme 是一个 Typora 主题，重点放在更平静的排版、更温和的明暗对比，以及更适合长文阅读的体验。

这是一个非官方 Typora 主题，灵感来自公开可见的视觉风格。它与 Anthropic 没有关联，也未获得 Anthropic 的认可或背书。

![typography](/screenshots/zh-light.png)
![typography](/screenshots/zh.png)
![code-dark](/screenshots/code-dark.png)

## 包含文件

- `clawlike.css`：浅色主题
- `clawlike-dark.css`：深色主题
- `clawlike/fonts/JetBrainsMono-Regular.woff2`：用于代码块和行内代码的等宽字体
- `theme-showcase.md`：用于截图和预览主题效果的示例文件
- `theme-showcase.en.md`：用于英文 README 截图的英文示例文件

## 文件结构

```text
Clawlike-TyporaTheme/
├── README.md
├── README.en.md
├── clawlike.css
├── clawlike-dark.css
├── theme-showcase.md
├── theme-showcase.en.md
└── clawlike/
    └── fonts/
        └── JetBrainsMono-Regular.woff2
```

## 设计方向

- 为长时间阅读准备的舒适留白和行距
- 标题使用更有编辑感的衬线风格，正文保持克制、稳定的无衬线阅读体验
- 使用偏暖的中性色，而不是生硬的纯白底色
- 为技术写作调校过的简洁代码块样式
- 表格去掉传统网格感，强调水平分隔、数字对齐和更像出版物的阅读节奏

## 示例文件

仓库内提供了 `theme-showcase.md` 和 `theme-showcase.en.md`，分别用于中文和英文截图预览。

这份文件集中展示了：

- 标题层级和正文排版
- 行内代码与代码块
- 引用、脚注、链接和键位样式
- 主题里单独调校过的表格系统

如果你准备为仓库补效果图，中文截图直接打开 `theme-showcase.md`，英文截图直接打开 `theme-showcase.en.md` 即可。

## 表格设计

这个主题的表格不是默认样式微调，而是按“更适合阅读”的方向重新整理过：

- 移除竖线和多余背景，只保留水平分隔，降低表单感
- 表头使用更紧凑的大写样式，方便快速扫读栏目
- 数字启用 `tabular-nums`，连续数字更整齐
- 单元格留白和最小宽度更大，长内容不容易挤作一团
- 第一列会稍微更稳一些，适合承载章节名或标签
- 保留横向滚动能力，窄窗口下不会直接破坏版式

## 安装方法

1. 打开 Typora。
2. 进入 `Settings` -> `Appearance`。
3. 打开 Typora 的主题目录。
4. 将 `clawlike.css`、`clawlike-dark.css` 和 `clawlike` 文件夹复制到该目录中。
5. 重启 Typora，或在主题菜单中切换到对应主题。

## 字体说明

如果希望获得预期中的视觉效果，请将以下字体文件放到 `themes/clawlike/fonts/` 目录下：

- `AnthropicSans-Roman-Web.woff2`
- `AnthropicSans-Italic-Web.woff2`
- `AnthropicSerif-Roman-Web.woff2`
- `AnthropicSerif-Italic-Web.woff2`

这些字体文件不随本主题分发，请自行通过合法渠道获取。如果缺少这些字体，主题会回退到仓库内置的字体栈。

如果你需要这些字体文件，可以自行搜索 `Anthropic font`。

## 说明

- 仓库内仅内置 `JetBrains Mono`，并且只用于等宽文本场景。
- 再次说明：这是一个受公开视觉风格启发的非官方 Typora 主题，与 Anthropic 没有关联，也未获得其认可或背书。

## 许可证

[MIT](LICENSE)
