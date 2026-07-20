---
title: "Gemini 1.5 Flash: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-14
lastmod: 2024-05-14
draft: false
weight: 10
model_id: "gemini-1-5-flash"
vendor: "google"
version: "1.5-flash"
tags: ["multimodal", "realtime", "long-context"]
---

# Gemini 1.5 Flash

## Model Overview

Google Gemini 1.5 Flash 经济型模型, 1M 上下文, 速度快成本低, 适合大规模多模态任务。

## Core Specifications

| Vendor | Version | Release Date | Context Window | Input Modalities | Output Modalities | License |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash | 2024-05-14 | 1000K | text, image, audio, video | text | Proprietary |

## Benchmark Performance

| Benchmark | Score | Unit | Notes |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.0 | % | 5-shot |
| HumanEval | 67.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.2 | % | 0-shot CoT |
| MATH | 53.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 38.5 | % | 0-shot |
| IFEval | 68.0 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 46.1 | % | 0-shot |
| WinoGrande | 78.9 | % | 0-shot |

## Pricing

| Input | Output | Cache Read | Cache Write |
|------|--------|-----------|-----------|
| — | — | — | — |

*per million tokens*

## Strengths

- Input Modalities: text, image, audio.
- Context window 1000K.

## Weaknesses

- Proprietary, not self-hostable.

## Use Cases

- Long document summarization
- Vision and image understanding

## References

- [Gemini 1.5 Flash Documentation](https://ai.google.dev/gemini-api/docs)
- Release Date: 2024-05-14
- Vendor: Google
