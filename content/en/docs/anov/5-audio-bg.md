---
title: "Play background music"
description: ""
summary: ""
date: 2025-02-03T21:44:00+09:00
lastmod: 2025-02-03T21:44:00+09:00
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

<!--
Alice Novel では、背景音楽の再生が可能です。

臨時ファイルを作成するため、画像と比較するとやや低速となっています。

※キャッシュ周りの仕様を変更したことにより、臨時ファイル作成後はやや高速な再生ができるようになりました。
-->

### Usage

Background music can be played by following `bgm: ` with a file name.

It is possible to interrupt background music that is already playing by writing only `bgm: `.

### Examples

```anov
bgm: bgm.wav
```

```anov
bgm: 
```

### 利用可能バージョン

- Alice Novel: v0.9.0-rc2 or later
- Alice Console: *Unsupported*
