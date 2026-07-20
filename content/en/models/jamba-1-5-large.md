---
title: "Jamba 1.5 Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba 1.5 Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
model_id: "jamba-1-5-large"
vendor: "other"
version: "jamba-1-5-large"
tags: ["open-weights", "moe", "long-context"]
---

# Jamba 1.5 Large

## Model Overview

AI21 Labs Jamba 1.5 Large 混合 SSM-Transformer 模型, 256K 上下文, 总参 398B/活跃 94B, 长上下文突出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-1-5-large | 2024-08-07 | 256K | text | text | Jamba Open Model License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 73.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 60.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.8 | % | 3-shot CoT |
| GPQA | 50.8 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 93.8 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 84.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 84.3, strong knowledge reasoning.
- Context window 256K.
- Mixture-of-Experts architecture.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization

## References

- [Jamba 1.5 Large Documentation](https://huggingface.co/models)
- Release Date: 2024-08-07
- Vendor: Other
