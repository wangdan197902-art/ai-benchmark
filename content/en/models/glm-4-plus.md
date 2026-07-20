---
title: "GLM-4 Plus: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Plus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-plus"
vendor: "other"
version: "glm-4-plus"
tags: ["flagship", "chinese", "multimodal"]
---

# GLM-4 Plus

## Model Overview

清华智谱 GLM-4 Plus 旗舰模型, 131K 上下文, 支持文本与图像输入, 中文能力突出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-plus | 2024-08-12 | 131K | text, image | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 72.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.8 | % | 0-shot CoT |
| MATH | 53.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.6 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 51.3 | % | 0-shot |
| WinoGrande | 85.8 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- MMLU score 84.3, strong knowledge reasoning.
- Input Modalities: text, image, audio.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Code generation and debugging
- Vision and image understanding
- Agent workflows and tool use

## References

- [GLM-4 Plus Documentation](https://huggingface.co/models)
- Release Date: 2024-08-12
- Vendor: Other
