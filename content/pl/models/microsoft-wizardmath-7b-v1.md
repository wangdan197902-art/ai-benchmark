---
title: "Microsoft WizardMath 7B v1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardMath 7B v1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-17
lastmod: 2023-08-17
draft: false
weight: 10
model_id: "microsoft-wizardmath-7b-v1"
vendor: "other"
version: "wizardmath-7b-v1"
tags: ["open-weights", "math", "self-hostable", "legacy"]
---

# Microsoft WizardMath 7B v1

## Przegląd modelu

Microsoft WizardMath 7B v1 数学专用模型, 4K 上下文, 基于 Llama 2 7B, 在 GSM8K 上达到 54.9%。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardmath-7b-v1 | 2023-08-17 | 4K | text | text | Llama 2 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.1 | % | 5-shot |
| HumanEval | 61.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.7 | % | 0-shot CoT |
| MATH | 65.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.4 | % | 3-shot CoT |
| GPQA | 30.2 | % | 0-shot |
| IFEval | 57.7 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 53.4 | % | 0-shot |
| WinoGrande | 70.5 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [Microsoft WizardMath 7B v1 Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-08-17
- Dostawca: Other
