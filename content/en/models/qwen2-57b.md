---
title: "Qwen2 57B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 57B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-57b"
vendor: "alibaba"
version: "2-57b"
tags: ["open-weights", "chinese", "moe"]
---

# Qwen2 57B

## Model Overview

阿里巴巴 Qwen2 57B MoE 开源模型, 131K 上下文, 总参 57B/活跃 14B, 性能与效率平衡。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-57b | 2024-06-07 | 131K | text | text | Qwen License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.7 | % | 5-shot |
| HumanEval | 67.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.3 | % | 0-shot CoT |
| MATH | 54.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.4 | % | 3-shot CoT |
| GPQA | 39.4 | % | 0-shot |
| IFEval | 71.2 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 50.5 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Mixture-of-Experts architecture.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Qwen2 57B Documentation](https://qwenlm.github.io/)
- Release Date: 2024-06-07
- Vendor: Alibaba
