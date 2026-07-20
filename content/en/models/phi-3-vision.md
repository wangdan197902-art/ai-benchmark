---
title: "Phi-3 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-vision"
vendor: "other"
version: "phi-3-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Phi-3 Vision

## Model Overview

Microsoft Phi-3 Vision 4.2B 多模态模型, 4K 上下文, 支持图像理解, 在 4B 规模上多模态能力领先。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-vision | 2024-05-21 | 4K | text, image | text | MIT |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.4 | % | 5-shot |
| HumanEval | 48.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.0 | % | 0-shot CoT |
| MATH | 24.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 40.1 | % | 3-shot CoT |
| GPQA | 17.4 | % | 0-shot |
| IFEval | 56.4 | % | prompt_strict |
| ARC | 77.4 | % | challenge |
| MUSR | 32.1 | % | 0-shot |
| WinoGrande | 74.7 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Input Modalities: text, image, audio.

## Weaknesses

- MMLU 56.4, weak knowledge reasoning.
- HumanEval 48.2, coding weak.
- Proprietary, not self-hostable.
- Context window 4K is limited.

## Use Cases

- Vision and image understanding

## References

- [Phi-3 Vision Documentation](https://huggingface.co/models)
- Release Date: 2024-05-21
- Vendor: Other
