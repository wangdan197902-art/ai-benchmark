---
title: "TigerBot 70B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of TigerBot 70B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-22
lastmod: 2023-08-22
draft: false
weight: 10
model_id: "tigerbot-70b-chat"
vendor: "other"
version: "tigerbot-70b-chat"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# TigerBot 70B Chat

## Model Overview

TigerLab TigerBot 70B Chat 中文对话模型, 4K 上下文, 基于 Llama 2 微调, 中文场景优化。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | tigerbot-70b-chat | 2023-08-22 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 71.7 | % | 5-shot |
| HumanEval | 36.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.1 | % | 0-shot CoT |
| MATH | 15.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.9 | % | 3-shot CoT |
| GPQA | 31.2 | % | 0-shot |
| IFEval | 55.7 | % | prompt_strict |
| ARC | 87.9 | % | challenge |
| MUSR | 39.3 | % | 0-shot |
| WinoGrande | 66.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- HumanEval 36.0, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [TigerBot 70B Chat Documentation](https://huggingface.co/models)
- Release Date: 2023-08-22
- Vendor: Other
