---
title: "Jurassic-2 Ultra: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jurassic-2 Ultra performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-01-12
lastmod: 2023-01-12
draft: false
weight: 10
model_id: "j2-ultra"
vendor: "other"
version: "j2-ultra"
tags: ["legacy", "flagship"]
---

# Jurassic-2 Ultra

## Modellöversikt

AI21 Labs Jurassic-2 Ultra 旗舰模型, 8K 上下文, 在 J2 系列中性能最强, 适合复杂推理任务。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | j2-ultra | 2023-01-12 | 8K | text | text | Proprietary |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.5 | % | 5-shot |
| HumanEval | 50.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.3 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.9 | % | 3-shot CoT |
| GPQA | 28.7 | % | 0-shot |
| IFEval | 47.9 | % | prompt_strict |
| ARC | 82.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Användningsområden

- Agent 工作流与工具调用

## Referenser

- [Jurassic-2 Ultra Dokumentation](https://huggingface.co/models)
- Releasedatum: 2023-01-12
- Leverantör: Other
