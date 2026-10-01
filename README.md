# blog

个人博客文章合集。文章以带日期前缀的 Markdown 放在 `articles/`，配图放在 `assets/`；主题用 front-matter 的 `tags` 标记，不再按主题文件夹分目录。

## 目录结构

```
blog/
  README.md
  articles/          # YYYY-MM-DD-slug.md，含 YAML front matter
  assets/<slug>/     # 文章配图
```

每篇文章 front matter 含：`title`、`tags`、`source`、`date`。正文在 front matter 之后，尽量忠实保留源页面内容。

> **路径变更**：原先的主题文件夹（如 `生活/`、`赚钱/`）已移除；请改用下方 `articles/` 链接。GitHub Pages 无正式重定向，旧路径将 404。

## 按时间

- [2021-06-12 · 对话吴军：赚大钱的逻辑](./articles/2021-06-12-dui-hua-wu-jun-zhuan-da-qian-de-luo-ji.md) — tags: 赚钱
- [2026-10-01 · 城市与抱负](./articles/2026-10-01-cities-and-ambition.md) — tags: 生活, 抱负

## 按标签

### 生活 / 抱负

- [城市与抱负](./articles/2026-10-01-cities-and-ambition.md) — Paul Graham《Cities and Ambition》中文译本（收录自 [PandaTalk8](https://pandatalk8.com/blog/cities-and-ambition)）

### 赚钱

- [对话吴军：赚大钱的逻辑](./articles/2021-06-12-dui-hua-wu-jun-zhuan-da-qian-de-luo-ji.md) — 正和岛对话吴军（收录自 [虎嗅网](https://www.huxiu.com/article/434479.html)）

## 来源说明

文章正文尽量忠实保留源页面内容；原链接见各篇 front matter 的 `source` 字段及文内说明。
