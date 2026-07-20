---
title: "StableLM 3 4B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 3 4B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-26
lastmod: 2024-06-26
draft: false
weight: 10
model_id: "stablelm-3-4b"
vendor: "other"
version: "stablelm-3-4b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 3 4B

## Model Overview

Stability AI StableLM 3 4B 模型, 4K 上下文, 多语言 (English/Spanish/German/Italian/French)。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-3-4b | 2024-06-26 | 4K | text | text | Stability AI Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.6 | % | 5-shot |
| HumanEval | 32.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.1 | % | 0-shot CoT |
| MATH | 11.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.9 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 36.6 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 50.6, weak knowledge reasoning.
- HumanEval 32.6, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [StableLM 3 4B Documentation](https://huggingface.co/models)
- Release Date: 2024-06-26
- Vendor: Other
