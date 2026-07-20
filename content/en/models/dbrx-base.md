---
title: "DBRX Base: Complete Benchmark Performance Guide"
description: "In-depth analysis of DBRX Base performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-base"
vendor: "other"
version: "dbrx-base"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Base

## Model Overview

Databricks DBRX Base 基础 MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 适合企业定制微调。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-base | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.9 | % | 5-shot |
| HumanEval | 72.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.4 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 39.3 | % | 0-shot |
| IFEval | 79.3 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 53.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Mixture-of-Experts architecture.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging

## References

- [DBRX Base Documentation](https://huggingface.co/models)
- Release Date: 2024-03-27
- Vendor: Other
