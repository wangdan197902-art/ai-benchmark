---
title: "Phi-3 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-22
lastmod: 2024-04-22
draft: false
weight: 10
model_id: "phi-3-mini"
vendor: "other"
version: "phi-3-mini"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Mini

## Model Overview

Microsoft Phi-3 Mini 3.8B 轻量模型, 4K 上下文 (可扩展 128K), 训练数据高质量, 性能超越 Llama 2 7B。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-mini | 2024-04-22 | 4K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 43.6 | % | 5-shot |
| HumanEval | 26.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.9 | % | 0-shot CoT |
| MATH | 17.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.9 | % | 3-shot CoT |
| GPQA | 20.7 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 84.4 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 67.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 43.6, weak knowledge reasoning.
- HumanEval 26.9, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Phi-3 Mini Documentation](https://huggingface.co/models)
- Release Date: 2024-04-22
- Vendor: Other
