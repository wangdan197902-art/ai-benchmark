---
title: "Yi Large Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Large Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
model_id: "yi-large-turbo"
vendor: "other"
version: "yi-large-turbo"
tags: ["flagship", "chinese", "realtime"]
---

# Yi Large Turbo

## Model Overview

01.AI Yi Large Turbo 经济型旗舰, 16K 上下文, 速度快成本低, 性能接近 Yi Large。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-large-turbo | 2024-07-24 | 16K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 72.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.0 | % | 0-shot CoT |
| MATH | 42.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.4 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 95.6 | % | challenge |
| MUSR | 63.7 | % | 0-shot |
| WinoGrande | 82.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 84.4, strong knowledge reasoning.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 16K is limited.

## Use Cases

- Code generation and debugging
- Agent workflows and tool use

## References

- [Yi Large Turbo Documentation](https://huggingface.co/models)
- Release Date: 2024-07-24
- Vendor: Other
