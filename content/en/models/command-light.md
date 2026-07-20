---
title: "Command Light: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command Light performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "command-light"
vendor: "cohere"
version: "light"
tags: ["legacy", "realtime"]
---

# Command Light

## Model Overview

Cohere Command Light 经济型模型, 4K 上下文, 速度快成本低, 适合简单任务与高吞吐场景。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | light | 2023-09-14 | 4K | text | text | CC-BY-NC-4.0 |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.8 | % | 5-shot |
| HumanEval | 51.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 39.8 | % | 0-shot CoT |
| MATH | 24.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.5 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 53.9 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 40.7 | % | 0-shot |
| WinoGrande | 74.7 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Reliable general-purpose model.

## Weaknesses

- MMLU 52.8, weak knowledge reasoning.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- General chat and Q&A

## References

- [Command Light Documentation](https://docs.cohere.com/docs)
- Release Date: 2023-09-14
- Vendor: Cohere
