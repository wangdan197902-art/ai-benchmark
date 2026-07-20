---
title: "Mistral Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-large"
vendor: "mistral"
version: "large"
tags: ["flagship", "eu-residency"]
---

# Mistral Large

## Model Overview

Mistral AI Large 首代旗舰, 32K 上下文, 多语言与推理能力突出, 原生支持函数调用与 JSON 输出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large | 2024-02-26 | 32K | text | text | Apache 2.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.0 | % | 5-shot |
| HumanEval | 73.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.7 | % | 3-shot CoT |
| GPQA | 38.1 | % | 0-shot |
| IFEval | 75.8 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 52.1 | % | 0-shot |
| WinoGrande | 83.3 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 82.0, strong knowledge reasoning.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Agent workflows and tool use

## References

- [Mistral Large Documentation](https://docs.mistral.ai/)
- Release Date: 2024-02-26
- Vendor: Mistral
