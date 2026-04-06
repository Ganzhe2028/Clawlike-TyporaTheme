# Clawlike Theme

[简体中文](README.md)

Clawlike Theme is a Typora theme focused on calm typography, warm color contrast, and long-form readability.

This is an unofficial Typora theme inspired by a public visual style. It is not affiliated with or endorsed by Anthropic.

## Included files

- `clawlike.css`: light theme
- `clawlike-dark.css`: dark theme
- `clawlike/fonts/JetBrainsMono-Regular.woff2`: monospace font for code blocks and inline code
- `theme-showcase.md`: sample file for screenshots and quick theme preview

## File structure

```text
Clawlike-TyporaTheme/
├── README.md
├── clawlike.css
├── clawlike-dark.css
├── theme-showcase.md
└── clawlike/
    └── fonts/
        └── JetBrainsMono-Regular.woff2
```

## Design direction

- Comfortable spacing for long reading sessions
- Editorial serif headings with restrained sans-serif body text
- Warm neutral palette instead of stark pure white
- Clean code blocks tuned for technical writing
- Tables are tuned for calmer scanning, with fewer borders, steadier numeric alignment, and a more editorial reading rhythm

## Sample File

The repository includes `theme-showcase.md` for quick previewing and screenshots in Typora.

It is designed to show:

- heading hierarchy and body spacing
- inline code and fenced code blocks
- blockquotes, footnotes, links, and keyboard key styling
- the table treatment that was tuned specifically for this theme

If you want to add screenshots to the repository, open `theme-showcase.md` and capture the sections you need.

## Table Design

The table styling is not a minor tweak of the default Typora table. It was adjusted for technical reading:

- vertical lines and extra background treatments are removed to reduce grid noise
- headers use a tighter uppercase treatment for faster scanning
- numbers use `tabular-nums` so adjacent values compare more cleanly
- cells have more breathing room and a larger minimum width
- wide tables can scroll horizontally instead of collapsing the layout

## Installation

1. Open Typora.
2. Go to `Settings` -> `Appearance`.
3. Open the Typora themes folder.
4. Copy `clawlike.css`, `clawlike-dark.css`, and the `clawlike` folder into that directory.
5. Restart Typora or switch themes from the theme menu.

## Fonts

For the intended appearance, place these files under `themes/clawlike/fonts/`:

- `AnthropicSans-Roman-Web.woff2`
- `AnthropicSans-Italic-Web.woff2`
- `AnthropicSerif-Roman-Web.woff2`
- `AnthropicSerif-Italic-Web.woff2`

These font files are not distributed with this theme. Please obtain them yourself from lawful sources. If they are unavailable, the theme will fall back to the bundled font stack.

For these font files, just Google `Anthropic font`.

## Notes

- `JetBrains Mono` is bundled only for monospace usage.
- AGAIN: This is an UNOFFICIAL Typora theme inspired by a public visual style. It is NOT affiliated with or endorsed by Anthropic.

## LICENSE

[MIT](LICENSE)
