---
title: "Zephyr 7B Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Zephyr 7B Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-25
lastmod: 2023-10-25
draft: false
weight: 10
model_id: "zephyr-7b-beta"
vendor: "other"
version: "zephyr-7b-beta"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Zephyr 7B Beta

## Model Overview

HuggingFaceH4 Zephyr 7B Beta 对话模型, 4K 上下文, 基于 Mistral 7B DPO 微调, 性能接近 GPT-3.5。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-7b-beta | 2023-10-25 | 4K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.1 | % | 5-shot |
| HumanEval | 38.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 50.4 | % | 0-shot CoT |
| MATH | 31.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.0 | % | 3-shot CoT |
| GPQA | 28.6 | % | 0-shot |
| IFEval | 51.2 | % | prompt_strict |
| ARC | 81.8 | % | challenge |
| MUSR | 32.6 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- HumanEval 38.4, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Zephyr 7B Beta Documentation](https://huggingface.co/models)
- Release Date: 2023-10-25
- Vendor: Other
