---
title: "Codestral Mamba: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral Mamba performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-16
lastmod: 2024-07-16
draft: false
weight: 10
model_id: "codestral-mamba"
vendor: "mistral"
version: "codestral-mamba"
tags: ["coding", "open-weights", "long-context"]
---

# Codestral Mamba

## Model Overview

Mistral Codestral Mamba 7B 代码模型, 256K 上下文, 基于 Mamba 架构, 线性时间复杂度适合长序列。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral-mamba | 2024-07-16 | 256K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 59.3 | % | 5-shot |
| HumanEval | 86.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 67.8 | % | 0-shot CoT |
| MATH | 28.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 65.5 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- HumanEval 86.2, excellent code generation.
- Context window 256K.

## Weaknesses

- MMLU 59.3, weak knowledge reasoning.
- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Long document summarization

## References

- [Codestral Mamba Documentation](https://docs.mistral.ai/)
- Release Date: 2024-07-16
- Vendor: Mistral
