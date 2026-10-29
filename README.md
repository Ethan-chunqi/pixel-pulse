# UXUY Narrative Studio

UXUY 内容工作台：面向社区、项目方、上市公司（潜在合作伙伴），组合共用内容积木并演示完整方案。

A bilingual narrative workspace for UXUY, with shared content blocks for the community, project teams and listed companies (potential partners).

## Website

https://ethan-chunqi.github.io/pixel-pulse/

- 中文：`?lang=zh`
- English: `?lang=en`
- 28 blocks, three audiences, responsive canvas, full story reader, presentation and Markdown export.
- Edits and story selections are saved in the current browser. Use the backup controls to transfer content between devices. Chinese and English content are maintained separately.

## Update content

- `content.json`: Chinese content and recommended audience routes.
- `content.en.json`: English content with matching block IDs.
- `index.html`, `styles.css`, `app.js`: the static application.
- `uxuy-logo.svg`, `favicon.svg`, `UXUY-Sans-SC.woff2`: local brand and font assets.

GitHub Pages serves the root of the `main` branch. Changes committed here are published automatically by GitHub Pages. All asset paths are relative, so the website works under `/pixel-pulse/`.

## Run locally

```sh
python3 -m http.server 4173
```

Open http://localhost:4173/ . No install or build step is required.

## Fonts

The subsetted Noto Sans SC font is distributed under the SIL Open Font License. See `OFL.txt`. UXUY brand marks retain their original geometry.
