---
title: "Mixtral 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Mixtral 8x22B across MMLU, HumanEval, GSM8K, MATH, and BBH benchmarks with pricing and self-hosting considerations."
date: 2024-04-10
lastmod: 2024-08-15
draft: false
weight: 50
model_id: "mixtral-8x22b"
vendor: "mistral"
version: "8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x22B

## Model Overview

Mixtral 8x22B is Mistral AI's open-weights sparse mixture-of-experts (MoE) model, released on April 10, 2024. The architecture combines 8 expert networks of 22B parameters each, totaling 141B parameters but activating only ~39B per token. This design delivers performance comparable to dense 70B+ models at roughly one-third the inference cost. The model supports a 64K context window and handles English, French, Italian, German, and Spanish with strong multilingual capability. Released under Apache 2.0, Mixtral 8x22B is one of the few frontier-class models available for unrestricted commercial use, including fine-tuning, redistribution, and integration into proprietary products. It is widely deployed through inference providers such as Together AI, Fireworks AI, and self-hosted on consumer-accessible GPU clusters.

## Key Specifications

| Attribute | Value |
|-----------|-------|
| Vendor | Mistral AI |
| Version | 8x22b |
| Release Date | 2024-04-10 |
| Context Window | 64,000 tokens |
| Input Modalities | text |
| Output Modalities | text |
| License | Apache 2.0 |
| Documentation | https://docs.mistral.ai/ |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|-----------|-------|------|-------|
| MMLU | 77.8 | % | 5-shot |
| HumanEval | 45.2 | pass@1 | — |
| GSM8K | 78.6 | % | 0-shot CoT |
| MATH | 46.0 | % | 0-shot CoT |
| BBH | 74.5 | % | 3-shot CoT |

## Pricing

| Tier | Price (per 1M tokens) |
|------|------------------------|
| Input (Mistral hosted) | $1.20 |
| Output (Mistral hosted) | $1.20 |
| Cache Read | $0.00 |
| Cache Write | $0.00 |

Pricing source: https://mistral.ai/technology/ (as of 2024-08-01). Apache 2.0 license allows unrestricted self-hosting.

## Strengths

- Apache 2.0 license enables unrestricted commercial use, including redistribution.
- MoE architecture delivers strong performance-per-FLOP at inference time.
- Strong multilingual capability across five major European languages.
- Lower inference cost than dense models of comparable size.

## Weaknesses

- Coding performance (HumanEval 45.2) significantly trails flagship models.
- 64K context window is smaller than newer open-weights competitors.
- MoE serving requires careful routing and memory management for optimal throughput.

## Use Cases

- Cost-sensitive multilingual text generation in European markets.
- On-premise customer service or RAG pipelines with permissive licensing.
- Research and education use cases requiring Apache 2.0 compliance.
- Foundation for fine-tuned domain-specific variants.

## References

- [Mixtral 8x22B Announcement — Mistral AI](https://mistral.ai/news/mixtral-8x22b/)
- [Mistral AI Documentation](https://docs.mistral.ai/)
- [Mistral Technology Page](https://mistral.ai/technology/)
