---
title: "Phi-1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "phi-1"
vendor: "other"
version: "phi-1"
tags: ["open-weights", "coding", "self-hostable", "legacy"]
---

# Phi-1

## Przegląd modelu

Microsoft Phi-1 1.3B 代码模型, 2K 上下文, 专为代码生成训练, 在 1.3B 规模上 HumanEval 表现突出。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-1 | 2023-09-14 | 2K | text | text | MIT |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.1 | % | 5-shot |
| HumanEval | 88.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.6 | % | 0-shot CoT |
| MATH | 25.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.9 | % | 3-shot CoT |
| GPQA | 22.1 | % | 0-shot |
| IFEval | 53.8 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 49.0 | % | 0-shot |
| WinoGrande | 74.5 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- HumanEval 88.1, excellent code generation.

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [Phi-1 Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-09-14
- Dostawca: Other
