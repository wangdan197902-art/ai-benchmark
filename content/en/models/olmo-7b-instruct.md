---
title: "OLMo 7B Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 7B Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-01
lastmod: 2024-02-01
draft: false
weight: 10
model_id: "olmo-7b-instruct"
vendor: "other"
version: "olmo-7b-instruct"
tags: ["open-weights", "self-hostable"]
---

# OLMo 7B Instruct

## Model Overview

AllenAI OLMo 7B Instruct 指令微调版本, 2K 上下文, 改进指令遵循能力, 适合对话与助手场景。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-7b-instruct | 2024-02-01 | 2K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.6 | % | 5-shot |
| HumanEval | 50.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.7 | % | 0-shot CoT |
| MATH | 34.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.5 | % | 3-shot CoT |
| GPQA | 30.5 | % | 0-shot |
| IFEval | 63.6 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 42.5 | % | 0-shot |
| WinoGrande | 78.9 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 2K is limited.

## Use Cases

- General chat and Q&A

## References

- [OLMo 7B Instruct Documentation](https://huggingface.co/models)
- Release Date: 2024-02-01
- Vendor: Other
