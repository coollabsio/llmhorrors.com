---
title: "GPT-5.6-Sol deletes almost all files on a user's Mac"
description: "A GPT-5.6-Sol review subagent expanded $HOME incorrectly in a cleanup command and recursively deleted material from the user's home directory."
tags:
  - gpt-5-6-sol
  - openai
  - data-loss
  - coding-agent
author: Andras Bacsai
authorTwitter: heyandras
date: "2026-07-10T19:03:52.006Z"
image: /assets/gpt-5-6-sol-mac-file-deletion.png
category: development
isNew: true
---

__tldr: GPT-5.6-Sol accidentally deleted almost all files on a user's Mac after a review subagent expanded $HOME incorrectly and ran a recursive deletion command against the user's home directory.__

[Original post](https://x.com/mattshumer_/status/2075657271401390161)

Conclusion: Coding agents must sandbox destructive commands and require explicit confirmation before deleting files outside the project workspace.
