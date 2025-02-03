---
title: "How to create"
description: ""
summary: ""
date: 2025-02-03T21:52:00+09:00
lastmod: 2025-02-03T21:52:00+09:00
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

### How to create

The Anproj file format uses the ZIP format. And so, you can create it anywhere with the environment to create ZIP file.

{{< tabs "create-anproj-file" >}}
{{< tab "ZIP" >}}

### ZIP Archiver

This way uses a ZIP Archiver.

1. Create necessary files such as `package.json`, `main.anov` and others.
    ```
    .
    ├── img/pictures
    ├── story
    │     └── main.anov
    └── package.json
    ```
1. Archive whole of files to ZIP. (IMPORTANT: Instead of compressing the root file, select all at the root location and compress)
1. Change the file name from `**.zip` to `**.anproj`.

{{< /tab >}}
{{< tab "Alice Console" >}}

### Alice Console

This way uses the `pack` command in Alice Console.

1. Create necessary files such as `package.json`, `main.anov` and others with `init` command.
    ```sh
    aliceconsole init
    ```
1. A directory called `AnprojTemplate` will be created, so run the `pack` command against this directory.
    ```sh
    aliceconsole pack <directory>
    # Example: aliceconsole pack ./AnprojTemplate/
    ```
1. Created the `AnprojTemplate.anproj` file.

{{< /tab >}}
{{< /tabs >}}

Then, the Anproj file was created. You can open it in Alice Novel.

### Reference

- [Sample Games](https://github.com/AliceNovel/SampleGames)

### Version Information

- Alice Novel: *Unsupported*
- Alice Console: Later the next release (v0.3.0)
