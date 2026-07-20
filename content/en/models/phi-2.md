---
title: "Phi-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "phi-2"
vendor: "other"
version: "phi-2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-2

## Model Overview

Microsoft Phi-2 2.7B 模型, 2K 上下文, 在 2.7B 规模上推理能力突出, 适合研究/教育用途。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-2 | 2023-12-11 | 2K | text | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.5 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.8 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.8 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 48.8 | % | prompt_strict |
| ARC | 75.1 | % | challenge |
| MUSR | 23.7 | % | 0-shot |
| WinoGrande | 72.8 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 57.5, weak knowledge reasoning.
- HumanEval 39.7, coding weak.
- Proprietary, not self-hostable.
- Context window 2K is limited.

## Use Cases

- General chat and Q&A

## References

- [Phi-2 Documentation](https://huggingface.co/models)
- Release Date: 2023-12-11
- Vendor: Other
