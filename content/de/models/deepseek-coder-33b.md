---
title: "DeepSeek Coder 33B: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder 33B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "deepseek-coder-33b"
vendor: "deepseek"
version: "coder-33b"
tags: ["open-weights", "coding", "self-hostable"]
---

# DeepSeek Coder 33B

## Modellübersicht

DeepSeek Coder 33B 代码专用开源模型, 16K 上下文, 33B 参数, 性能接近 GPT-3.5, 开源代码模型旗舰。

## Kernspezifikationen

| Anbieter | Version | Veröffentlichungsdatum | Kontextfenster | Eingabemodalitäten | Ausgabemodalitäten | Lizenz |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-33b | 2024-01-25 | 16K | text | text | DeepSeek License |

## Benchmark-Leistung

| Benchmark | Ergebnis | Einheit | Notizen |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.9 | % | 5-shot |
| HumanEval | 71.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 32.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 61.6 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 58.8 | % | prompt_strict |
| ARC | 92.2 | % | challenge |
| MUSR | 45.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

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

- 代码生成与调试

## Referenzen

- [DeepSeek Coder 33B Dokumentation](https://api-docs.deepseek.com/)
- Veröffentlichungsdatum: 2024-01-25
- Anbieter: Deepseek
