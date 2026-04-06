# Clawlike Theme Showcase

这是一份专门用于截图的示例文档。建议在 Typora 中分别切换 `Clawlike` 和 `Clawlike Dark` 打开它，直接截取不同区块。

## Typography

Clawlike Theme 想要呈现的是更安静的阅读节奏。标题偏向 editorial 的 serif 语气，正文保持克制，链接、`inline code`、==高亮== 和 **强调文本** 会各自占据清晰但不过分吵闹的位置。

这一段适合展示正文密度、留白、链接样式和段落之间的呼吸感。你也可以顺手测试一个链接，比如 [Typora](https://typora.io)，再看一下 `Command Palette` 这类短代码在正文中的视觉重量是否合适。这里补一个脚注引用，方便一起展示小字排版。[^1]

> 好的主题不只是“好看”，而是让长文写作时的注意力更稳定。

### Writing Rhythm

- Serif 标题负责拉开层次
- Sans 正文负责稳定阅读
- `JetBrains Mono` 负责代码语义
- `==Mark==` 和链接负责低强度提示

1. 打开 Typora
2. 切换到 `Clawlike`
3. 滚动到表格区域
4. 截一张你想放进 README 的图

- [x] 任务列表会保留整洁的阅读节奏
- [ ] 未完成项也不会显得太跳

### Shortcuts

按下 <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> 可以快速打开命令面板，按下 <kbd>Cmd</kbd> + <kbd>/</kbd> 可以切换源码视图。

## Code

```ts
type Section = {
  title: string;
  minutes: number;
  mood: "calm" | "focused";
};

const sections: Section[] = [
  { title: "Typography", minutes: 6, mood: "calm" },
  { title: "Code", minutes: 4, mood: "focused" },
  { title: "Tables", minutes: 5, mood: "focused" },
];

const summary = sections.map((section) => {
  return `${section.title}: ${section.minutes} min`;
});

console.log(summary.join(" | "));
```

```bash
cp clawlike.css ~/Library/Application\ Support/abnerworks.Typora/themes/
cp clawlike-dark.css ~/Library/Application\ Support/abnerworks.Typora/themes/
```

## Table Details

下面这张表适合展示这个主题在表格上的处理：大写表头、无竖线、只有水平分隔、数字更容易纵向比较，宽表也不会把页面挤坏。

| Section | Focus Score | Reading Time | Token Budget | Review Pass | Notes |
| :-- | --: | --: | --: | --: | :-- |
| Opening | 92 | 03.5 min | 1,280 | 2 | 第一列会稍微更稳一些，适合放名称或章节标签。 |
| Typography | 96 | 06.0 min | 2,400 | 3 | 数字使用更适合对比的排版方式，连续看几列也不会发散。 |
| Code Samples | 88 | 04.5 min | 1,920 | 2 | 表格不使用竖线，信息之间依靠留白和横向分隔来组织。 |
| Wide Table Check | 90 | 05.0 min | 3,840 | 4 | 列数变多时会保留横向滚动空间，而不是把内容压得很碎。 |
| Final Screenshot | 94 | 02.0 min | 640 | 1 | 这一行可以专门拿来观察浅色和深色主题下的边界控制。 |

下面这张表故意做得更宽一些，方便直接观察横向滚动和留白控制。

| Surface Area | Divider Strategy | Numeric Alignment | Minimum Width Rule | Overflow Behavior | First Column Weight | Screenshot Value |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Reading Notes | 只保留水平分隔，让扫描路径更顺 | `03.5`、`06.0`、`1,280` 这类数字会更整齐 | 每列保留更大的最小宽度，避免内容挤成碎片 | 窄窗口下允许横向滚动，不会强行压缩布局 | 第一列略微加重，适合放章节或标签 | 很适合单独截一张表格近景 |
| Review Snapshot | 不用竖线去制造秩序，而是靠留白分层 | 连续指标放在一起时更容易纵向比较 | 长表头仍然有呼吸空间，不会贴得很紧 | 宽表仍能保持页面外轮廓稳定 | 第一列的视觉锚点会更明显 | 很适合展示 light / dark 的边界变化 |

## Mixed Content

分隔线、引用、列表和代码之间的切换，也应该维持同一套节奏感。

---

> 如果你想把截图放进仓库，优先截取 `Typography`、`Code` 和 `Table Details` 这三个区块。

## Closing Note

这份文件的目的不是写满功能，而是让主题的主要气质在一页内都能看见。

[^1]: 脚注区域适合观察小号文字、行距和次级信息的存在感。
