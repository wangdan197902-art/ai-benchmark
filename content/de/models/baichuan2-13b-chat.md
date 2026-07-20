---
title: "Baichuan2 13B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of Baichuan2 13B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
model_id: "baichuan2-13b-chat"
vendor: "other"
version: "baichuan2-13b-chat"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Baichuan2 13B Chat

## Modellübersicht

百川智能 Baichuan2 13B Chat 对话模型, 4K 上下文, 中英双语能力突出, 适合中文场景部署。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | baichuan2-13b-chat | 2023-09-06 | 4K | text | text | Baichuan 2 License |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.6 | % | 5-shot |
| HumanEval | 49.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 41.0 | % | 0-shot CoT |
| MATH | 23.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 64.2 | % | 3-shot CoT |
| GPQA | 34.7 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 83.2 | % | challenge |
| MUSR | 37.9 | % | 0-shot |
| WinoGrande | 69.5 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- MMLU 仅 58.6，知识推理偏弱。
- HumanEval 49.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Anwendungsfälle

- 通用对话与问答

## Referenzen

- [Baichuan2 13B Chat Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2023-09-06
- Anbieter: Other
