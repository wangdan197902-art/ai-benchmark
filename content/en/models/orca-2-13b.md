---
title: "Orca 2 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Orca 2 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-20
lastmod: 2023-11-20
draft: false
weight: 10
model_id: "orca-2-13b"
vendor: "other"
version: "orca-2-13b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Orca 2 13B

## Model Overview

Microsoft Orca 2 13B 推理增强模型, 4K 上下文, 基于 Llama 2 微调, 通过渐进式复杂任务训练提升推理。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | orca-2-13b | 2023-11-20 | 4K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 74.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.1 | % | 0-shot CoT |
| MATH | 42.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.8 | % | 3-shot CoT |
| GPQA | 42.5 | % | 0-shot |
| IFEval | 74.2 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 59.8 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- Code generation and debugging

## References

- [Orca 2 13B Documentation](https://huggingface.co/models)
- Release Date: 2023-11-20
- Vendor: Other
