---
title: "Nous Hermes 2 Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-22
lastmod: 2024-01-22
draft: false
weight: 10
model_id: "nous-hermes-2-yi-34b"
vendor: "other"
version: "nous-hermes-2-yi-34b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Nous Hermes 2 Yi 34B

## Modellübersicht

NousResearch Hermes 2 Yi 34B 微调模型, 4K 上下文, 基于 Yi 34B, 改进多语言与指令遵循。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-yi-34b | 2024-01-22 | 4K | text | text | Apache 2.0 |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 73.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.7 | % | 0-shot CoT |
| MATH | 44.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 39.0 | % | 0-shot |
| IFEval | 68.3 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 48.8 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Anwendungsfälle

- 代码生成与调试

## Referenzen

- [Nous Hermes 2 Yi 34B Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2024-01-22
- Anbieter: Other
