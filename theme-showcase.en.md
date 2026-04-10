---
title: Clawlike Theme Showcase
lang: en
theme-check:
  - yaml-front-matter
  - typography
  - tables
---

# Clawlike Theme Showcase

This sample is designed for screenshots. Open it in Typora with both `Clawlike` and `Clawlike Dark` and capture the sections you want.

## Typography

Clawlike Theme aims for a quieter reading rhythm. The headings lean editorial and serif-driven, while the body text stays restrained. Links, `inline code`, ==highlights==, and **emphasis** each hold a clear place without competing for attention.

This paragraph is useful for showing body density, spacing, link styling, and the breathing room between paragraphs. You can also test a real link such as [Typora](https://typora.io) and see whether short inline fragments like `Command Palette` carry the right visual weight. Here is a footnote reference as well, so the small-text treatment appears in the same screenshot.[^1]

> A good theme is not only attractive. It keeps your attention steady while you write and reread longer documents.

### Writing Rhythm

- Serif headings create hierarchy
- Sans body text keeps long reading stable
- `JetBrains Mono` carries code semantics
- `==Mark==` and links provide low-intensity emphasis

### Mixed Script Baseline Check

These lines are here to expose mixed Chinese, English, punctuation, and numerals. The CJK glyphs should stay visually aligned instead of sinking below the Latin baseline:

0. 总写作策略

1. Identity & Growth（约 300 words）

Paragraph 1 | Starting point + core conflict（约 140-160 words）

This mixed line is useful for body text: 本周完成 3 次 review、2 轮修改，最后留下一个更清楚的 narrative.

1. Open Typora
2. Switch to `Clawlike`
3. Scroll to the table section
4. Capture the frame you want for the README

- [x] Task lists stay tidy and readable
- [ ] Unfinished items still feel calm rather than noisy

### Shortcuts

Press <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> to open the command palette quickly, and press <kbd>Cmd</kbd> + <kbd>/</kbd> to toggle source mode.

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

The first table is useful for showing the table treatment in this theme: uppercase headers, no vertical rules, horizontal dividers only, numbers that compare cleanly, and enough width to keep the layout from feeling compressed.

| Section | Focus Score | Reading Time | Token Budget | Review Pass | Notes |
| :-- | --: | --: | --: | --: | :-- |
| Opening | 92 | 03.5 min | 1,280 | 2 | The first column carries a little more weight, which works well for labels and section names. |
| Typography | 96 | 06.0 min | 2,400 | 3 | Numbers are set up for cleaner comparison, so several metric columns can sit together without feeling messy. |
| Code Samples | 88 | 04.5 min | 1,920 | 2 | The table avoids vertical lines and relies on spacing plus horizontal dividers to organize information. |
| Wide Table Check | 90 | 05.0 min | 3,840 | 4 | As the table gets wider, the layout keeps room for horizontal scrolling instead of crushing every column. |
| Final Screenshot | 94 | 02.0 min | 640 | 1 | This row is a good place to compare edge control in both light and dark mode. |

The second table is intentionally wider, so you can capture the horizontal scroll behavior and the spacing more directly.

| Surface Area | Divider Strategy | Numeric Alignment | Minimum Width Rule | Overflow Behavior | First Column Weight | Screenshot Value |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Reading Notes | Horizontal dividers guide the eye without building a heavy grid | Values like `03.5`, `06.0`, and `1,280` line up more cleanly | Each column keeps more minimum space so long content does not collapse into clutter | Narrow windows can scroll sideways instead of forcing a broken layout | The first column acts as a stronger anchor for labels | This is a strong close-up table shot |
| Review Snapshot | Order comes from whitespace rather than vertical rules | Adjacent metrics are easier to compare line by line | Longer headers still keep breathing room | Wide tables stay stable inside the page frame | The label column remains visually steady | This works well for comparing light and dark screenshots |

## Mixed Content

The transition between dividers, quotes, lists, and code should still feel like one continuous rhythm.

---

> If you want screenshots for the repository, prioritize `Typography`, `Code`, and `Table Details`.

## Closing Note

The goal of this file is not to show every Markdown feature. It is to make the character of the theme visible within a single page.

[^1]: Footnotes are a good place to inspect small-text sizing, line height, and the presence of secondary information.
