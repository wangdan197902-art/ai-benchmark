---
title: "GPT-4o mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4o mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
model_id: "gpt-4o-mini"
vendor: "openai"
version: "4o-mini"
tags: ["multimodal", "realtime"]
---

# GPT-4o mini

## Model Overview

OpenAI 经济型多模态模型, 128K 上下文, 支持文本与图像输入, 平衡成本与性能, 适合大规模部署。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4o-mini | 2024-07-18 | 128K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.7 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.1 | % | 0-shot CoT |
| MATH | 51.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 67.9 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 53.1 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Input Modalities: text, image, audio.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Vision and image understanding

## References

- [GPT-4o mini Documentation](https://platform.openai.com/docs/models)
- Release Date: 2024-07-18
- Vendor: Openai
