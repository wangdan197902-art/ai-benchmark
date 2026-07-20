---
title: "Baichuan2 7B Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of Baichuan2 7B Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-06
lastmod: 2023-09-06
draft: false
weight: 10
model_id: "baichuan2-7b-chat"
vendor: "other"
version: "baichuan2-7b-chat"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Baichuan2 7B Chat

## Modellübersicht

百川智能 Baichuan2 7B Chat 经济型对话模型, 4K 上下文, 7B 参数, 适合本地中文场景部署。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | baichuan2-7b-chat | 2023-09-06 | 4K | text | text | Baichuan 2 License |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.9 | % | 5-shot |
| HumanEval | 49.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.0 | % | 0-shot CoT |
| MATH | 18.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 33.5 | % | 0-shot |
| IFEval | 50.1 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 33.1 | % | 0-shot |
| WinoGrande | 68.3 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- MMLU 仅 57.9，知识推理偏弱。
- HumanEval 49.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Anwendungsfälle

- 通用对话与问答

## Referenzen

- [Baichuan2 7B Chat Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2023-09-06
- Anbieter: Other
