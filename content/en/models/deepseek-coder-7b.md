---
title: "DeepSeek Coder 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "deepseek-coder-7b"
vendor: "deepseek"
version: "coder-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# DeepSeek Coder 7B

## Model Overview

DeepSeek Coder 7B 代码专用开源模型, 16K 上下文, 7B 参数, 在 7B 规模上代码生成能力领先。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-7b | 2024-01-25 | 16K | text | text | DeepSeek License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.6 | % | 5-shot |
| HumanEval | 75.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 54.7 | % | 0-shot CoT |
| MATH | 32.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.7 | % | 3-shot CoT |
| GPQA | 23.9 | % | 0-shot |
| IFEval | 55.4 | % | prompt_strict |
| ARC | 86.3 | % | challenge |
| MUSR | 50.5 | % | 0-shot |
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

- [DeepSeek Coder 7B Documentation](https://api-docs.deepseek.com/)
- Release Date: 2024-01-25
- Vendor: Deepseek
