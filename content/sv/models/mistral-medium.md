---
title: "Mistral Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mistral-medium"
vendor: "mistral"
version: "medium"
tags: ["eu-residency"]
---

# Mistral Medium

## Modellöversikt

Mistral AI Medium 中端模型, 32K 上下文, 平衡性能与成本, 适合企业级通用任务。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | medium | 2023-12-11 | 32K | text | text | Apache 2.0 |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.9 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 54.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 48.7 | % | 0-shot |
| IFEval | 77.4 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 82.4 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- MMLU score 82.9, strong knowledge reasoning.

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 代码生成与调试

## Referenser

- [Mistral Medium Dokumentation](https://docs.mistral.ai/)
- Releasedatum: 2023-12-11
- Leverantör: Mistral
