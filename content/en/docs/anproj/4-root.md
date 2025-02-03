---
title: "Root directories"
description: ""
summary: ""
date: 2025-02-03T22:24:00+09:00
lastmod: 2025-02-03T22:24:00+09:00
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

### Summary

You can set the root directories for the each kinds.

- State: Optional

| Key | Initial state |
| - | - |
| `root-image` | "image/" |
| `root-background` | "image/background/" |
| `root-story` | "story/" |
| `root-data` | "data/" |
| `root-chara` | "character.json" |
| `root-save` | "save/" |
| `root-audio` | "audio/" |
| `root-movie` | "movie/" |

### Example

```package.json
{
  "root-image": "img/",
  "root-background": "img/bg/",

  "root-story": "story/"
}
```

### Version Informations

- Alice Novel: v0.9.0-rc2 or later
- Alice Console: *Unsupported*
