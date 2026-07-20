---
title: "Jurassic-2 Mid: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jurassic-2 Mid performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-01-12
lastmod: 2023-01-12
draft: false
weight: 10
model_id: "j2-mid"
vendor: "other"
version: "j2-mid"
tags: ["legacy"]
---

# Jurassic-2 Mid

## Model Overview

AI21 Labs Jurassic-2 Mid 中型模型, 8K 上下文, 多语言文本生成, 适合企业级内容创作。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | j2-mid | 2023-01-12 | 8K | text | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.9 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 33.2 | % | 0-shot CoT |
| MATH | 20.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.8 | % | 3-shot CoT |
| GPQA | 25.7 | % | 0-shot |
| IFEval | 49.8 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 32.3 | % | 0-shot |
| WinoGrande | 67.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 55.9, weak knowledge reasoning.
- HumanEval 39.7, coding weak.
- Proprietary, not self-hostable.
- Context window 8K is limited.

## Use Cases

- General chat and Q&A

## References

- [Jurassic-2 Mid Documentation](https://huggingface.co/models)
- Release Date: 2023-01-12
- Vendor: Other
