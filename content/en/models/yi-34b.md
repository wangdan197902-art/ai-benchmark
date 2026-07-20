---
title: "Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
model_id: "yi-34b"
vendor: "other"
version: "yi-34b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Yi 34B

## Model Overview

01.AI Yi 34B 首代开源模型, 4K 上下文, 340 亿参数, 在开源模型中曾排名第一。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-34b | 2023-11-05 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.5 | % | 5-shot |
| HumanEval | 35.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.3 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 20.6 | % | 0-shot |
| IFEval | 48.2 | % | prompt_strict |
| ARC | 87.2 | % | challenge |
| MUSR | 36.8 | % | 0-shot |
| WinoGrande | 71.5 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 55.5, weak knowledge reasoning.
- HumanEval 35.8, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Yi 34B Documentation](https://huggingface.co/models)
- Release Date: 2023-11-05
- Vendor: Other
