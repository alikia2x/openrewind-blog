---
title: 'Text recognition acceleration across platforms'
description: 'Supporting 3 different platforms with 6 CPU architecture combinations, this article describes how OpenRewind achieves efficient and stable text recognition.'
pubDate: 'Dec 28 2024'
heroImage: '/img/Cross Platform OCR.jpg'
---

## macOS

We first focused on macOS, which was our first target during development and is also the target for [rewind.ai](https://rewind.ai).

Fortunately, the [VisionKit](https://developer.apple.com/documentation/visionkit) provided by macOS is very powerful and sufficient for our use.

Therefore, we looked for a wrapper for VisionKit, a command line utility: [ocrit](https://github.com/insidegui/ocrit/).
