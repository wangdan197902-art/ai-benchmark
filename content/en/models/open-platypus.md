---
title: "Open-Platypus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Open-Platypus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-15
lastmod: 2023-09-15
draft: false
weight: 10
model_id: "open-platypus"
vendor: "other"
version: "open-platypus"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Open-Platypus

## Model Overview

Garage bAInd Open-Platypus 数据集与模型, 2K 上下文, 基于 Llama 2 微调, 适合 STEM 推理任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | open-platypus | 2023-09-15 | 2K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.7 | % | 5-shot |
| HumanEval | 48.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.9 | % | 0-shot CoT |
| MATH | 21.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.7 | % | 3-shot CoT |
| GPQA | 34.9 | % | 0-shot |
| IFEval | 46.0 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 40.0 | % | 0-shot |
| WinoGrande | 66.7 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- HumanEval 48.2, coding weak.
- Proprietary, not self-hostable.
- Context window 2K is limited.

## Use Cases

- General chat and Q&A

## References

- [Open-Platypus Documentation](https://huggingface.co/models)
- Release Date: 2023-09-15
- Vendor: Other
