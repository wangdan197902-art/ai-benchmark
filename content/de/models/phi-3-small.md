---
title: "Phi-3 Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-small"
vendor: "other"
version: "phi-3-small"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Small

## Modellübersicht

Microsoft Phi-3 Small 7.4B 模型, 8K 上下文, 在 7B 规模上推理能力突出, 适合移动设备部署。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-small | 2024-05-21 | 8K | text | text | MIT |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 71.8 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.7 | % | 0-shot CoT |
| MATH | 43.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 61.0 | % | prompt_strict |
| ARC | 89.6 | % | challenge |
| MUSR | 36.5 | % | 0-shot |
| WinoGrande | 74.9 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Anwendungsfälle

- 通用对话与问答

## Referenzen

- [Phi-3 Small Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2024-05-21
- Anbieter: Other
