---
title: "Phi-3.5 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3.5 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-mini"
vendor: "other"
version: "phi-3-5-mini"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Phi-3.5 Mini

## Model Overview

Microsoft Phi-3.5 Mini 3.8B 模型, 128K 上下文, 改进多语言与长上下文能力, 适合边缘部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-mini | 2024-08-16 | 128K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.7 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 22.1 | % | 0-shot CoT |
| MATH | 9.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.5 | % | 3-shot CoT |
| GPQA | 24.4 | % | 0-shot |
| IFEval | 48.7 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 31.2 | % | 0-shot |
| WinoGrande | 68.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Context window 128K.

## Weaknesses

- MMLU 55.7, weak knowledge reasoning.
- HumanEval 44.0, coding weak.
- Proprietary, not self-hostable.

## Use Cases

- Long document summarization

## References

- [Phi-3.5 Mini Documentation](https://huggingface.co/models)
- Release Date: 2024-08-16
- Vendor: Other
