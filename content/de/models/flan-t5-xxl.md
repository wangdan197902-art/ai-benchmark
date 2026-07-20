---
title: "Flan-T5 XXL: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-T5 XXL performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-12-07
lastmod: 2022-12-07
draft: false
weight: 10
model_id: "flan-t5-xxl"
vendor: "other"
version: "flan-t5-xxl"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-T5 XXL

## Modellübersicht

Google Flan-T5 XXL 11B 指令微调模型, 4K 上下文, 多任务指令微调, 零样本能力突出。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-t5-xxl | 2022-12-07 | 4K | text | text | Apache 2.0 |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 52.0 | % | 5-shot |
| HumanEval | 35.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 35.2 | % | 0-shot CoT |
| MATH | 21.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 28.6 | % | 0-shot |
| IFEval | 51.3 | % | prompt_strict |
| ARC | 81.7 | % | challenge |
| MUSR | 42.2 | % | 0-shot |
| WinoGrande | 74.2 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- MMLU 仅 52.0，知识推理偏弱。
- HumanEval 35.4，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Anwendungsfälle

- 通用对话与问答

## Referenzen

- [Flan-T5 XXL Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2022-12-07
- Anbieter: Other
