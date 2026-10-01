# blog

个人博客文章合集：正文 Markdown 在 `content/posts/`，配图在 `content/media/`。主题用 front matter 的 `tags` 标记。

## 按时间

- [2021-06-12 · 对话吴军：赚大钱的逻辑](./content/posts/2021-06-12-earn-big-money-logic-wu-jun.md) — [虎嗅网](https://www.huxiu.com/article/434479.html)
- [2026-10-01 · 城市与抱负](./content/posts/2026-10-01-cities-and-ambition.md) — [PandaTalk8](https://pandatalk8.com/blog/cities-and-ambition)

## 按标签

### 赚钱

- [对话吴军：赚大钱的逻辑](./content/posts/2021-06-12-earn-big-money-logic-wu-jun.md) — [虎嗅网](https://www.huxiu.com/article/434479.html)

### 生活

- [城市与抱负](./content/posts/2026-10-01-cities-and-ambition.md) — [PandaTalk8](https://pandatalk8.com/blog/cities-and-ambition)

### 抱负

- [城市与抱负](./content/posts/2026-10-01-cities-and-ambition.md) — [PandaTalk8](https://pandatalk8.com/blog/cities-and-ambition)

## 目录结构

```
blog/
  README.md
  content/
    posts/              # YYYY-MM-DD-slug.md（YAML front matter）
    media/<slug>/       # 文章配图
```

每篇文章 front matter 顺序：`title`、`date`、`tags`、`source`。正文在 front matter 之后，尽量忠实保留源页面内容。
