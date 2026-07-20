---
title: "Llama 3.2 90B Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.2 90B Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-90b-vision"
vendor: "meta"
version: "3.2-90b-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Llama 3.2 90B Vision

## Model Overview

Meta Llama 3.2 90B Vision 多模态开源模型, 128K 上下文, 支持图像理解, 性能接近 GPT-4V。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-90b-vision | 2024-09-25 | 128K | text, image | text | Llama 3.2 Community License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.5 | % | 5-shot |
| HumanEval | 73.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.6 | % | 0-shot CoT |
| MATH | 52.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.1 | % | 3-shot CoT |
| GPQA | 42.2 | % | 0-shot |
| IFEval | 74.5 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 53.5 | % | 0-shot |
| WinoGrande | 79.3 | % | 0-shot |

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

- [Llama 3.2 90B Vision Documentation](https://llama.meta.com/docs/)
- Release Date: 2024-09-25
- Vendor: Meta
