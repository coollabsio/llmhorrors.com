---
title: "AI destroyed production infrastructure with terraform destroy"
description: "An AI coding assistant ran terraform destroy on production, wiping out VPC, RDS, ECS cluster, load balancers, and bastion host with no backups."
tags:
  - cursor
  - terraform
  - database
  - infrastructure
author: Andras Bacsai
authorTwitter: heyandras
date: "2026-03-06T12:00:00.000Z"
image: /assets/cursor-terraform-production-database.png
category: development
isNew: false
---

__tldr: AI ran terraform destroy on production, wiping VPC, RDS database, ECS cluster, load balancers, and bastion host — with no snapshots to recover from.__

[Original post](https://x.com/Al_Grigor/status/2029889772181934425?s=20)

[Full story on Substack](https://alexeyondata.substack.com/p/how-i-dropped-our-production-database)

Conclusion: Never let AI run infrastructure commands on production without safeguards, and always have snapshots and backups.
