---
title: "StarCoder2 15B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarCoder2 15B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-15b"
vendor: "other"
version: "starcoder2-15b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 15B

## Model Overview

BigCode StarCoder2 15B 代码专用开源模型, 16K 上下文, 训练于 80+ 编程语言, 代码生成能力突出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-15b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.6 | % | 5-shot |
| HumanEval | 73.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.6 | % | 0-shot CoT |
| MATH | 46.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.8 | % | 3-shot CoT |
| GPQA | 35.3 | % | 0-shot |
| IFEval | 59.6 | % | prompt_strict |
| ARC | 87.6 | % | challenge |
| MUSR | 51.7 | % | 0-shot |
| WinoGrande | 70.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 16K is limited.

## Use Cases

- Code generation and debugging

## References

- [StarCoder2 15B Documentation](https://huggingface.co/models)
- Release Date: 2024-02-28
- Vendor: Other
