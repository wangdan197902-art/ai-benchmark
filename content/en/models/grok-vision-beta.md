---
title: "Grok Vision Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok Vision Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-vision-beta"
vendor: "xai"
version: "vision-beta"
tags: ["multimodal", "legacy"]
---

# Grok Vision Beta

## Model Overview

xAI Grok Vision Beta 早期多模态预览版, 8K 上下文, 支持图像理解, 集成 X 平台实时信息。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | vision-beta | 2023-11-04 | 8K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.3 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 35.2 | % | 0-shot CoT |
| MATH | 24.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 56.8 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 46.8 | % | prompt_strict |
| ARC | 88.2 | % | challenge |
| MUSR | 44.5 | % | 0-shot |
| WinoGrande | 67.5 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Input Modalities: text, image, audio.

## Weaknesses

- HumanEval 44.0, coding weak.
- Proprietary, not self-hostable.
- Context window 8K is limited.

## Use Cases

- Vision and image understanding

## References

- [Grok Vision Beta Documentation](https://docs.x.ai/)
- Release Date: 2023-11-04
- Vendor: Xai
