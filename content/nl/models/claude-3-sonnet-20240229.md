---
title: "Claude 3 Sonnet (2024-02-29): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Sonnet (2024-02-29) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-29
lastmod: 2024-02-29
draft: false
weight: 10
model_id: "claude-3-sonnet-20240229"
vendor: "anthropic"
version: "3-sonnet-20240229"
tags: ["multimodal", "long-context"]
---

# Claude 3 Sonnet (2024-02-29)

## Modeloverzicht

Anthropic Claude 3 Sonnet 2024-02-29 快照版本, 200K 上下文, 速度与智能平衡型。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-sonnet-20240229 | 2024-02-29 | 200K | text, image | text | Proprietary |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.0 | % | 5-shot |
| HumanEval | 80.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.6 | % | 0-shot CoT |
| MATH | 46.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.2 | % | 3-shot CoT |
| GPQA | 41.7 | % | 0-shot |
| IFEval | 75.5 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 63.5 | % | 0-shot |
| WinoGrande | 80.3 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- MMLU score 84.0, strong knowledge reasoning.
- HumanEval 80.1, excellent code generation.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解

## Referenties

- [Claude 3 Sonnet (2024-02-29) Documentatie](https://docs.anthropic.com/claude/docs)
- Releasedatum: 2024-02-29
- Leverancier: Anthropic
