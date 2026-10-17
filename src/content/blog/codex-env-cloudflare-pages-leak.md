---
title: "Codex publishes .env to Cloudflare Pages, leaked key runs up $89k Google bill"
description: "Codex deployed a project's .env file to Cloudflare Pages. The leaked Google API key was used to run Fable 5.1 swarms, which caused an $88,982.85 bill."
tags:
  - codex
  - openai
  - cloudflare
  - security
  - cost
author: Andras Bacsai
authorTwitter: heyandras
date: "2026-10-15T20:05:16.000Z"
image: /assets/codex-env-cloudflare-pages-leak.png
category: development
isNew: true
---

__tldr: Codex published a user's .env file to Cloudflare Pages. Someone took the Google API key and ran fable-5.1-max swarms while the user slept, which caused an $88,982.85 bill. Opus 5.5 found the cause; Codex could not find it, did not explain, and flagged the chat as a cybersecurity risk.__

[Original post](https://x.com/JustLingonberry/status/2110824346168238204)

[First post about the bill](https://x.com/JustLingonberry/status/2108982107846619209)

Conclusion: Never let an agent deploy without a check of what goes into the build output. Keep secrets out of deploy folders, and set budget limits and key restrictions on every cloud API key.
