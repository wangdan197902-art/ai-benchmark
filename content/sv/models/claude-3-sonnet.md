---
title: "Claude 3 Sonnet: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Sonnet performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-sonnet"
vendor: "anthropic"
version: "3-sonnet"
tags: ["multimodal", "long-context"]
---

# Claude 3 Sonnet

## Modellöversikt

Anthropic Claude 3 Sonnet 平衡型模型, 200K 上下文, 在速度与智能间取得平衡, 适合企业级部署。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-sonnet | 2024-03-04 | 200K | text, image | text | Proprietary |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.5 | % | 5-shot |
| HumanEval | 74.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 42.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.1 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 64.1 | % | 0-shot |
| WinoGrande | 83.8 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- MMLU score 81.5, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解

## Referenser

- [Claude 3 Sonnet Dokumentation](https://docs.anthropic.com/claude/docs)
- Releasedatum: 2024-03-04
- Leverantör: Anthropic
