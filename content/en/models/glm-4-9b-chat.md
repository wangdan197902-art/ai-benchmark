---
title: "GLM-4 9B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 9B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-05
lastmod: 2024-06-05
draft: false
weight: 10
model_id: "glm-4-9b-chat"
vendor: "other"
version: "glm-4-9b-chat"
tags: ["open-weights", "chinese", "self-hostable", "multimodal"]
---

# GLM-4 9B Chat

## Model Overview

清华智谱 GLM-4 9B Chat 开源对话模型, 131K 上下文, 9B 参数, 支持图像理解, 中英双语突出。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-9b-chat | 2024-06-05 | 131K | text, image | text | GLM-4 License |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 70.7 | % | 5-shot |
| HumanEval | 62.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.0 | % | 0-shot CoT |
| MATH | 26.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 67.2 | % | 3-shot CoT |
| GPQA | 37.2 | % | 0-shot |
| IFEval | 59.9 | % | prompt_strict |
| ARC | 88.6 | % | challenge |
| MUSR | 49.5 | % | 0-shot |
| WinoGrande | 79.4 | % | 0-shot |

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

- Vision and image understanding

## References

- [GLM-4 9B Chat Documentation](https://huggingface.co/models)
- Release Date: 2024-06-05
- Vendor: Other
