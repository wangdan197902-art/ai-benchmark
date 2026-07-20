---
title: "DeepSeek Coder 33B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder 33B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "deepseek-coder-33b"
vendor: "deepseek"
version: "coder-33b"
tags: ["open-weights", "coding", "self-hostable"]
---

# DeepSeek Coder 33B

## Model Overview

DeepSeek Coder 33B 代码专用开源模型, 16K 上下文, 33B 参数, 性能接近 GPT-3.5, 开源代码模型旗舰。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-33b | 2024-01-25 | 16K | text | text | DeepSeek License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.9 | % | 5-shot |
| HumanEval | 71.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 32.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 61.6 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 58.8 | % | prompt_strict |
| ARC | 92.2 | % | challenge |
| MUSR | 45.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

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

- [DeepSeek Coder 33B Documentation](https://api-docs.deepseek.com/)
- Release Date: 2024-01-25
- Vendor: Deepseek
