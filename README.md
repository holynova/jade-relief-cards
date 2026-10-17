# Jade Relief Cards / 玉石浮雕扑克牌艺术馆

中文：玉石浮雕扑克牌艺术馆：收录名著、漫画、游戏三大系列 75 张精美玉雕扑克牌，支持分类筛选、3D 翻牌互动与全卡流光特效。

English: Jade relief playing card art gallery featuring 75 intricate jade-carved cards across classics, manga, and games, with 3D flip interaction and category filtering.

![Project screenshot](./assets/screenshot.png)

## 在线体验 / Live Demo

- [Cloudflare Demo](https://xiaosang.cc/jade-relief-cards/)
- [GitHub Repo](https://github.com/holynova/jade-relief-cards)

<img src="./assets/qr.png" width="180" alt="扫码访问 Cloudflare 在线体验">

## 本地运行 / Run locally

```bash
python3 -m http.server 8000
```

## 发布 / Deploy

```bash
npx wrangler deploy --config wrangler.jsonc
```

Cloudflare Workers · Domain: `xiaosang.cc` · Route: `/jade-relief-cards/`

源码与部署配置使用同一个主分支（main）；在本地手动发布，不创建 Cloudflare 专用分支或 GitHub Action。
