---
title: "Cursor agent deletes Railway production volume in 9 seconds"
description: "Cursor running Claude Opus 4.6 made a single GraphQL volumeDelete call that wiped PocketOS production data and all volume-level backups."
tags:
  - cursor
  - railway
  - claude-opus
  - database
  - infrastructure
author: Andras Bacsai
authorTwitter: heyandras
date: "2026-04-26T12:00:00.000Z"
image: /assets/cursor-railway-volume-deletion.png
category: development
isNew: true
---

__tldr: Cursor agent (Claude Opus 4.6) made a single Railway GraphQL volumeDelete call that wiped PocketOS production data and all volume-level backups in 9 seconds. Most recent recoverable backup was 3 months old.__

[Original post](https://x.com/lifeof_jer/status/2048103471019434248)

Conclusion: Destructive APIs need confirmation steps that an agent cannot auto-complete, tokens must be scopable, and "volume backups" stored inside the same volume are not backups.
