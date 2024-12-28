---
title: 'Text recognition acceleration across platforms'
description: 'Supporting 3 different platforms with 6 CPU architecture combinations, this article describes how OpenRewind achieves efficient and stable text recognition.'
pubDate: 'Dec 28 2024'
heroImage: '/img/Cross Platform OCR.jpg'
---

## macOS

macOS was our initial focus during development, as it's the primary target for [rewind.ai](https://rewind.ai).

Leveraging the power of Apple's [VisionKit](https://developer.apple.com/documentation/visionkit) framework was a natural choice for our OCR needs. 

To streamline integration, we opted for a command-line utility that provides a wrapper around VisionKit: [ocrit](https://github.com/insidegui/ocrit/). This approach simplified the process and allowed us to efficiently extract text from images within our macOS environment.
