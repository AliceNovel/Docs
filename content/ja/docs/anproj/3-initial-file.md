---
title: "初期ロードファイル"
description: ""
summary: ""
date: 2023-12-11T19:24:00+09:00
lastmod: 2024-12-17T17:35:00+09:00
draft: false
slug: "3"
weight: 603
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

### 説明

初回ロード時に読み込むファイルを設定できます。

- キー: `first-read`
- 状態: **推奨**
- 初期設定: "main.anov"

### 例

```package.json
{
  "first-read": "story/main.anov"
}
```

### 利用可能バージョン

- Alice Novel: v0.9.0-rc1 以降
- Alice Console: *未実装*
