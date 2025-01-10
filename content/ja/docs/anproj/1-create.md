---
title: "作成方法"
description: ""
summary: ""
date: 2023-11-05T17:55:00+09:00
lastmod: 2024-12-25T23:24:00+09:00
draft: false
slug: "1"
weight: 601
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

### 作成方法

結論から言うと、Anproj 形式は ZIP 形式を利用しています。つまり ZIP ファイルを作成できる環境さえあれば、どこでも Alice Novel のゲームが作成できるのです。

{{< tabs "create-anproj-file" >}}
{{< tab "ZIP" >}}

### ZIP を使う

Windows や Linux に搭載されている標準の ZIP Archiver を利用する方法です。

1. `package.json` や `main.anov` などの必要なファイルを作成します。
    ```
    .
    ├── img/pictures
    ├── story
    │     └── main.anov
    └── package.json
    ```
1. ファイル全体を ZIP で圧縮します。(注意: ルートのファイルを圧縮するのではなく、ルートの位置で、全選択し、圧縮してください)
1. `**.zip` を `**.anproj` に変更します。

{{< /tab >}}
{{< tab "Alice Console" >}}

### Alice Console を使う

Alice Console の `pack` コマンドを利用します。

1. `package.json` や `main.anov` などの必要なファイルを作成します。
    ```sh
    aliceconsole init
    ```
1. `AnprojTemplate` というディレクトリが作成されるため、このディレクトリに対して `pack` コマンドを実行します。
    ```sh
    aliceconsole pack <directory>
    # 例: aliceconsole pack ./AnprojTemplate/
    ```
1. `AnprojTemplate.anproj` が生成されます。

{{< /tab >}}
{{< /tabs >}}

以上で、Anproj ファイルの作成ができました。これは、Alice Novel で開くことができます。

### 関連リンク

- [サンプルゲーム](https://github.com/AliceNovel/SampleGames)

### 利用可能バージョン

- Alice Novel: *未実装*
- Alice Console: 次期リリース (v0.3.0) 以降
