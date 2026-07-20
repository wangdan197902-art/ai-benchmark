---
title: "Nous Hermes 2 Solar 10.7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Solar 10.7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-solar-10-7b"
vendor: "other"
version: "nous-hermes-2-solar-10-7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Solar 10.7B

## Model Overview

NousResearch Hermes 2 Solar 10.7B 微调模型, 4K 上下文, 基于 Solar 10.7B, 性能接近 Llama 2 70B。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-solar-10-7b | 2024-02-19 | 4K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 59.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 37.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 39.6 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

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

- General chat and Q&A

## References

- [Nous Hermes 2 Solar 10.7B Documentation](https://huggingface.co/models)
- Release Date: 2024-02-19
- Vendor: Other
