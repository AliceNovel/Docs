---
title: "背景音楽を再生する"
description: ""
summary: ""
date: 2023-11-05T05:52:00+09:00
lastmod: 2024-12-16T23:38:00+09:00
draft: false
slug: "5"
weight: 505
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

Alice Novel では、背景音楽の再生が可能です。

臨時ファイルを作成するため、画像と比較するとやや低速となっています。

※キャッシュ周りの仕様を変更したことにより、臨時ファイル作成後はやや高速な再生ができるようになりました。

### 実装方法

`bgm: ` に続けてファイル名を指定することで背景音楽を再生できます。

`bgm: ` のみ書くことで、すでに再生されている背景音楽を中断することが可能です。

### 例

```anov
bgm: bgm.wav
```

```anov
bgm: 
```

### 利用可能バージョン

- Alice Novel: v0.9.0-rc2 以降
- Alice Console: *未対応*
