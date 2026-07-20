---
title: "Mistral Tiny: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Tiny performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-tiny"
vendor: "mistral"
version: "tiny"
tags: ["realtime", "legacy"]
---

# Mistral Tiny

## Model Overview

Mistral AI Tiny 经济型模型, 32K 上下文, 基于 Mistral 7B, 价格最低, 适合简单任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | tiny | 2024-02-26 | 32K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 54.2 | % | 5-shot |
| HumanEval | 45.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 57.2 | % | 0-shot CoT |
| MATH | 16.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.3 | % | 3-shot CoT |
| GPQA | 28.7 | % | 0-shot |
| IFEval | 51.7 | % | prompt_strict |
| ARC | 82.4 | % | challenge |
| MUSR | 41.4 | % | 0-shot |
| WinoGrande | 66.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 54.2, weak knowledge reasoning.
- HumanEval 45.8, coding weak.
- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Mistral Tiny Documentation](https://docs.mistral.ai/)
- Release Date: 2024-02-26
- Vendor: Mistral
