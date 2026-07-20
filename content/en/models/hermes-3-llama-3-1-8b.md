---
title: "Hermes 3 Llama 3.1 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-8b"
vendor: "other"
version: "hermes-3-llama-3-1-8b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 8B

## Model Overview

NousResearch Hermes 3 Llama 3.1 8B 微调模型, 131K 上下文, 经济型开源模型, 适合本地部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-8b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.1 | % | 5-shot |
| HumanEval | 67.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 72.9 | % | 0-shot CoT |
| MATH | 25.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.6 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 60.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 38.0 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- General chat and Q&A

## References

- [Hermes 3 Llama 3.1 8B Documentation](https://huggingface.co/models)
- Release Date: 2024-08-12
- Vendor: Other
