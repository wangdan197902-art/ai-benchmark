---
title: "Phi-4: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-4 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-12
lastmod: 2024-12-12
draft: false
weight: 10
model_id: "phi-4"
vendor: "other"
version: "phi-4"
tags: ["open-weights", "self-hostable", "reasoning"]
---

# Phi-4

## Modellübersicht

Microsoft Phi-4 14B 模型, 16K 上下文, 改进推理与数学能力, 在 14B 规模上接近 GPT-4o-mini。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-4 | 2024-12-12 | 16K | text | text | MIT |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.2 | % | 5-shot |
| HumanEval | 62.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 71.1 | % | 0-shot CoT |
| MATH | 39.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 30.1 | % | 0-shot |
| IFEval | 59.6 | % | prompt_strict |
| ARC | 85.1 | % | challenge |
| MUSR | 38.6 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Preise

| Eingabe | Ausgabe | Cache-Lesen | Cache-Schreiben |
|------|--------|-----------|-----------|
| — | — | — | — |

*pro Million Token*

## Stärken

- 可靠的通用模型。

## Schwächen

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Anwendungsfälle

- 通用对话与问答

## Referenzen

- [Phi-4 Dokumentation](https://huggingface.co/models)
- Veröffentlichungsdatum: 2024-12-12
- Anbieter: Other
