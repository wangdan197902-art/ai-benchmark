---
title: "Flan-T5 XXL: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-T5 XXL performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-12-07
lastmod: 2022-12-07
draft: false
weight: 10
model_id: "flan-t5-xxl"
vendor: "other"
version: "flan-t5-xxl"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-T5 XXL

## Model Overview

Google Flan-T5 XXL 11B 指令微调模型, 4K 上下文, 多任务指令微调, 零样本能力突出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-t5-xxl | 2022-12-07 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.0 | % | 5-shot |
| HumanEval | 35.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 35.2 | % | 0-shot CoT |
| MATH | 21.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 28.6 | % | 0-shot |
| IFEval | 51.3 | % | prompt_strict |
| ARC | 81.7 | % | challenge |
| MUSR | 42.2 | % | 0-shot |
| WinoGrande | 74.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 52.0, weak knowledge reasoning.
- HumanEval 35.4, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Flan-T5 XXL Documentation](https://huggingface.co/models)
- Release Date: 2022-12-07
- Vendor: Other
