---
title: "Llama 3.2 1B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 1B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-1b"
vendor: "meta"
version: "3.2-1b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.2 1B

## Model Overview

Meta Llama 3.2 1B 超轻量开源模型, 128K 上下文, 1B 参数, 适合资源受限设备与离线部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-1b | 2024-09-25 | 128K | text | text | Llama 3.2 Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 48.6 | % | 5-shot |
| HumanEval | 29.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.9 | % | 0-shot CoT |
| MATH | 11.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 38.8 | % | 3-shot CoT |
| GPQA | 22.6 | % | 0-shot |
| IFEval | 44.1 | % | prompt_strict |
| ARC | 75.9 | % | challenge |
| MUSR | 26.6 | % | 0-shot |
| WinoGrande | 64.0 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 48.6, weak knowledge reasoning.
- HumanEval 29.9, coding weak.
- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Llama 3.2 1B Documentation](https://llama.meta.com/docs/)
- Release Date: 2024-09-25
- Vendor: Meta
