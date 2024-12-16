---
title: "背景画像を表示する"
description: ""
summary: ""
date: 2023-11-05T05:52:00+09:00
lastmod: 2024-12-16T23:38:00+09:00
draft: false
slug: "4"
weight: 504
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

Alice Novel では、背景画像の表示が可能です。

臨時ファイルを作成しないため、比較的高速な表示が可能です。

(※現時点 (v0.9.3) ではキャラクターの顔画像や立ち絵を表示することはできません。今後実装を予定しています。)

### 実装方法

`> ` に続けてファイル名を指定することで背景画像を表示できます。

`> ` のみ書くことで、既に表示されている背景画像を非表示にできます。

### 例

```anov
> first-place.png
```

```anov
> 
```

### 利用可能バージョン

- Alice Novel: v0.9.0-rc1 以降
- Alice Console: *未対応*
