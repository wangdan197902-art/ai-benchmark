---
title: "Qwen2.5 1.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 1.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-1-5b"
vendor: "alibaba"
version: "2.5-1-5b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 1.5B

## Model Overview

阿里巴巴 Qwen2.5 1.5B 超轻量开源模型, 32K 上下文, 1.5B 参数, 适合资源受限设备部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-1-5b | 2024-09-19 | 32K | text | text | Qwen License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 54.5 | % | 5-shot |
| HumanEval | 35.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 33.2 | % | 0-shot CoT |
| MATH | 9.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.5 | % | 3-shot CoT |
| GPQA | 20.2 | % | 0-shot |
| IFEval | 41.9 | % | prompt_strict |
| ARC | 76.7 | % | challenge |
| MUSR | 37.8 | % | 0-shot |
| WinoGrande | 64.4 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 54.5, weak knowledge reasoning.
- HumanEval 35.2, coding weak.
- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Qwen2.5 1.5B Documentation](https://qwenlm.github.io/)
- Release Date: 2024-09-19
- Vendor: Alibaba
