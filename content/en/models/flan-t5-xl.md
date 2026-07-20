---
title: "Flan-T5 XL: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-T5 XL performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-12-07
lastmod: 2022-12-07
draft: false
weight: 10
model_id: "flan-t5-xl"
vendor: "other"
version: "flan-t5-xl"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-T5 XL

## Model Overview

Google Flan-T5 XL 3B 指令微调模型, 4K 上下文, 基于多任务指令微调, 适合零样本泛化任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-t5-xl | 2022-12-07 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.4 | % | 5-shot |
| HumanEval | 34.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.5 | % | 0-shot CoT |
| MATH | 27.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.5 | % | 3-shot CoT |
| GPQA | 22.6 | % | 0-shot |
| IFEval | 55.7 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 40.2 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- HumanEval 34.0, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Flan-T5 XL Documentation](https://huggingface.co/models)
- Release Date: 2022-12-07
- Vendor: Other
