---
title: "Mistral 7B v0.1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-27
lastmod: 2023-09-27
draft: false
weight: 10
model_id: "mistral-7b-v0.1"
vendor: "mistral"
version: "7b-v0.1"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.1

## Model Overview

Mistral 7B v0.1 首版开源模型, 8K 上下文, 7B 参数, 在所有 7B 模型中表现领先, Apache 2.0 可商用。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.1 | 2023-09-27 | 8K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.4 | % | 5-shot |
| HumanEval | 56.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.1 | % | 0-shot CoT |
| MATH | 26.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.4 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 58.9 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 37.4 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.
- Context window 8K is limited.

## Use Cases

- General chat and Q&A

## References

- [Mistral 7B v0.1 Documentation](https://docs.mistral.ai/)
- Release Date: 2023-09-27
- Vendor: Mistral
