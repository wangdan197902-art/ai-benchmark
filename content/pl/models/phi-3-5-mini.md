---
title: "Phi-3.5 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3.5 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-mini"
vendor: "other"
version: "phi-3-5-mini"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Phi-3.5 Mini

## Przegląd modelu

Microsoft Phi-3.5 Mini 3.8B 模型, 128K 上下文, 改进多语言与长上下文能力, 适合边缘部署。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-mini | 2024-08-16 | 128K | text | text | MIT |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.7 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 22.1 | % | 0-shot CoT |
| MATH | 9.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.5 | % | 3-shot CoT |
| GPQA | 24.4 | % | 0-shot |
| IFEval | 48.7 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 31.2 | % | 0-shot |
| WinoGrande | 68.6 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 上下文窗口 128K，支持长文本。

## Słabe strony

- MMLU 仅 55.7，知识推理偏弱。
- HumanEval 44.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 长文档摘要

## Referencje

- [Phi-3.5 Mini Dokumentacja](https://huggingface.co/models)
- Data wydania: 2024-08-16
- Dostawca: Other
