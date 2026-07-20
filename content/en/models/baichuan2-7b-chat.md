---
title: "Baichuan2 7B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of Baichuan2 7B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
model_id: "baichuan2-7b-chat"
vendor: "other"
version: "baichuan2-7b-chat"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Baichuan2 7B Chat

## Model Overview

百川智能 Baichuan2 7B Chat 经济型对话模型, 4K 上下文, 7B 参数, 适合本地中文场景部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | baichuan2-7b-chat | 2023-09-06 | 4K | text | text | Baichuan 2 License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.9 | % | 5-shot |
| HumanEval | 49.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.0 | % | 0-shot CoT |
| MATH | 18.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 33.5 | % | 0-shot |
| IFEval | 50.1 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 33.1 | % | 0-shot |
| WinoGrande | 68.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 57.9, weak knowledge reasoning.
- HumanEval 49.2, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Baichuan2 7B Chat Documentation](https://huggingface.co/models)
- Release Date: 2023-09-06
- Vendor: Other
