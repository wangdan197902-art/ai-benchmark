---
title: "StableLM 2 1.6B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 1.6B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-1-6b"
vendor: "other"
version: "stablelm-2-1-6b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 1.6B

## Model Overview

Stability AI StableLM 2 1.6B 轻量模型, 4K 上下文, 多语言训练, 适合移动设备部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-1-6b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.7 | % | 5-shot |
| HumanEval | 37.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.5 | % | 0-shot CoT |
| MATH | 26.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 40.7 | % | 3-shot CoT |
| GPQA | 15.0 | % | 0-shot |
| IFEval | 44.1 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 26.4 | % | 0-shot |
| WinoGrande | 70.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 52.7, weak knowledge reasoning.
- HumanEval 37.3, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [StableLM 2 1.6B Documentation](https://huggingface.co/models)
- Release Date: 2024-01-19
- Vendor: Other
