---
title: "OLMo 1.7 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 1.7 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-23
lastmod: 2024-08-23
draft: false
weight: 10
model_id: "olmo-1-7-7b"
vendor: "other"
version: "olmo-1-7-7b"
tags: ["open-weights", "self-hostable"]
---

# OLMo 1.7 7B

## Modellöversikt

AllenAI OLMo 1.7 7B 第二代模型, 4K 上下文, 改进训练流程, 性能超越初代 OLMo 7B。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-1-7-7b | 2024-08-23 | 4K | text | text | Apache 2.0 |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.5 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.5 | % | 0-shot CoT |
| MATH | 38.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 68.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 76.6 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Användningsområden

- 通用对话与问答

## Referenser

- [OLMo 1.7 7B Dokumentation](https://huggingface.co/models)
- Releasedatum: 2024-08-23
- Leverantör: Other
