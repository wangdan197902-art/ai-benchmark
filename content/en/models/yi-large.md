---
title: "Yi Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "yi-large"
vendor: "other"
version: "yi-large"
tags: ["flagship", "chinese"]
---

# Yi Large

## Model Overview

01.AI Yi Large 旗舰闭源模型, 32K 上下文, 中英文能力突出, 在 LMSYS 排行榜上接近 GPT-4。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-large | 2024-05-13 | 32K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.8 | % | 5-shot |
| HumanEval | 72.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.3 | % | 0-shot CoT |
| MATH | 55.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.1 | % | 3-shot CoT |
| GPQA | 35.2 | % | 0-shot |
| IFEval | 73.4 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 59.4 | % | 0-shot |
| WinoGrande | 84.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 82.8, strong knowledge reasoning.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Agent workflows and tool use

## References

- [Yi Large Documentation](https://huggingface.co/models)
- Release Date: 2024-05-13
- Vendor: Other
