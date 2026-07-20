---
title: "Llama Guard 2 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama Guard 2 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-guard-2-8b"
vendor: "meta"
version: "guard-2-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 2 8B

## Model Overview

Meta Llama Guard 2 8B 内容安全分类模型, 8K 上下文, 用于检测输入输出中的有害内容。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-2-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 26.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.3 | % | 0-shot CoT |
| MATH | 26.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.6 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 34.9 | % | 0-shot |
| WinoGrande | 66.5 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 51.0, weak knowledge reasoning.
- HumanEval 26.6, coding weak.
- Proprietary, not self-hostable.
- Context window 8K is limited.

## Use Cases

- General chat and Q&A

## References

- [Llama Guard 2 8B Documentation](https://llama.meta.com/docs/)
- Release Date: 2024-04-18
- Vendor: Meta
