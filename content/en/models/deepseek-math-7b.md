---
title: "DeepSeek Math 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Math 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-06
lastmod: 2024-02-06
draft: false
weight: 10
model_id: "deepseek-math-7b"
vendor: "deepseek"
version: "math-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# DeepSeek Math 7B

## Model Overview

DeepSeek Math 7B 数学专用开源模型, 4K 上下文, 在 MATH 基准上达到 64.7%, 7B 规模数学模型领先。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | math-7b | 2024-02-06 | 4K | text | text | DeepSeek License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.3 | % | 5-shot |
| HumanEval | 54.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.1 | % | 0-shot CoT |
| MATH | 53.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.9 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 61.1 | % | prompt_strict |
| ARC | 90.5 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [DeepSeek Math 7B Documentation](https://api-docs.deepseek.com/)
- Release Date: 2024-02-06
- Vendor: Deepseek
