---
title: "ルート"
description: ""
summary: ""
date: 2023-12-12T11:37:00+09:00
lastmod: 2024-12-17T17:37:00+09:00
draft: false
slug: "4"
weight: 604
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

### 説明

種類別のファイルのルートを設定できます。

- 状態: 任意

| キー | 役割 | 初期設定 |
| - | - | - |
| `root-image` | "image/" | 画像ディレクトリ |
| `root-background` | "image/background/" | 背景画像ディレクトリ |
| `root-story` | "story/" | ストーリーファイルのディレクトリ |
| `root-data` | "data/" | データディレクトリ |
| `root-chara` | "character.json" | キャラクターデータのファイル |
| `root-save` | "save/" | セーブ対象ディレクトリ |
| `root-audio` | "audio/" | 音声ディレクトリ |
| `root-movie` | "movie/" | 動画ディレクトリ |

### 例

```package.json
{
  "root-image": "img/",
  "root-background": "img/bg/",

  "root-story": "story/"
}
```

### 利用可能バージョン

- Alice Novel: v0.9.0-rc2 以降
- Alice Console: *未実装*
