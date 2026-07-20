---
title: "Yi 6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi 6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
model_id: "yi-6b"
vendor: "other"
version: "yi-6b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Yi 6B

## Model Overview

01.AI Yi 6B 经济型首代模型, 4K 上下文, 6B 参数, 适合本地部署与研究用途。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-6b | 2023-11-05 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.0 | % | 5-shot |
| HumanEval | 42.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 37.0 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.3 | % | 3-shot CoT |
| GPQA | 26.3 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 29.5 | % | 0-shot |
| WinoGrande | 72.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- HumanEval 42.3, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Yi 6B Documentation](https://huggingface.co/models)
- Release Date: 2023-11-05
- Vendor: Other
