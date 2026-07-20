---
title: "Code Llama 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-29
lastmod: 2024-01-29
draft: false
weight: 10
model_id: "code-llama-70b"
vendor: "meta"
version: "code-llama-70b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 70B

## Modellöversikt

Meta Code Llama 70B 代码专用开源模型, 16K 上下文, 基于 Llama 2 微调, 支持多语言代码生成。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-70b | 2024-01-29 | 16K | text | text | Llama 2 Community License |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.1 | % | 5-shot |
| HumanEval | 65.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 61.0 | % | 0-shot CoT |
| MATH | 34.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.1 | % | 3-shot CoT |
| GPQA | 25.3 | % | 0-shot |
| IFEval | 63.8 | % | prompt_strict |
| ARC | 89.8 | % | challenge |
| MUSR | 40.1 | % | 0-shot |
| WinoGrande | 75.5 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Användningsområden

- 代码生成与调试

## Referenser

- [Code Llama 70B Dokumentation](https://llama.meta.com/docs/)
- Releasedatum: 2024-01-29
- Leverantör: Meta
