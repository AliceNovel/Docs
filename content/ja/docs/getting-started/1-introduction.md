---
title: "はじめに"
description: "Get started with Anov Syntax"
summary: ""
date: 2024-12-18T18:08:00+09:00
lastmod: 2024-12-18T18:08:00+09:00
draft: false
slug: "1"
weight: 101
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

### 始める方法

Alice Project で開発している Anov 構文や Anproj 形式などの技術 (これらを総称して Alice System としています) を利用する方法はいくつか存在します。

以下に公式の方法を提示します。

- Alice Novel を使う
- Alice Console を使う

公式の方法以外にも、サードパーティー製のツールを使うことも可能です。

{{< tabs "create-new-site" >}}
{{< tab "Alice Novel" >}}

### Alice Novel を使う

Alice Novel は Alice Project が開発する最大のツールです。

#### インストール

1. https://github.com/AliceNovel/AliceNovel/releases/latest にアクセス
1. 下にスクロールし、`Assets` から `<os>-ci-build.zip` をダウンロード
1. ZIP ファイルを展開

これで、中の実行ファイルを利用することができます。

#### 利用方法

Alice Novel は `.anproj` ファイルを読み込むことができます。`.anov` ファイルの読み込みは現時点ではできませんが、開発中です。

{{< /tab >}}
{{< tab "Alice Console" >}}

### Alice Console を使う

Alice Console は Alice Project が開発する CLI ツールです。

#### インストール

1. https://github.com/AliceNovel/AliceConsole/releases/latest にアクセス
1. 下にスクロールし、`Assets` から `<os>-<architecture>.zip` をダウンロード
1. ZIP ファイルを展開

適切な権限付加させたあと、コマンドで利用できるようになります。

#### 利用方法

`.anov` ファイルを読み込むことができます。

```shell
# 例:
./AliceConsole main.anov
```

{{< /tab >}}
{{< /tabs >}}
