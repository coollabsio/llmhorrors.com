---
title: "Exposed key led to $2,500 in Stripe fees"
description: "A vibe-coded startup exposed API keys on the frontend; 175 customers were charged $500 before keys were rotated."
tags:
  - claude-code
  - stripe
  - security
  - api-key
author: Andras Bacsai
authorTwitter: heyandras
date: "2026-02-28T19:45:00.000Z"
image: /assets/claude-code-stripe-fee-loss.jpg
category: development
isNew: false
---

__tldr: Exposed keys in a vibe-coded app caused 175 fraudulent $500 charges and about $2,500 in Stripe fees before key rotation.__

[Original post](https://www.linkedin.com/posts/anton-karbanovich_my-vibe-coded-startup-was-exploited-i-lost-activity-7433538169922322432-Q_TZ/)

Conclusion: Keep API keys off the frontend and verify auth, rate limits, and abuse protections before launch.
