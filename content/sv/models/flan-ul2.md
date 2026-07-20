---
title: "Flan-UL2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-UL2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-03
lastmod: 2023-03-03
draft: false
weight: 10
model_id: "flan-ul2"
vendor: "other"
version: "flan-ul2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-UL2

## Modellöversikt

Google Flan-UL2 20B 指令微调模型, 4K 上下文, 基于 UL2 框架, 适合多任务与零样本推理。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-ul2 | 2023-03-03 | 4K | text | text | Apache 2.0 |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.7 | % | 5-shot |
| HumanEval | 46.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.6 | % | 0-shot CoT |
| MATH | 22.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 88.8 | % | challenge |
| MUSR | 37.2 | % | 0-shot |
| WinoGrande | 76.2 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- MMLU 仅 58.7，知识推理偏弱。
- HumanEval 46.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Användningsområden

- 通用对话与问答

## Referenser

- [Flan-UL2 Dokumentation](https://huggingface.co/models)
- Releasedatum: 2023-03-03
- Leverantör: Other
