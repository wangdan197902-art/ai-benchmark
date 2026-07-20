---
title: "Microsoft WizardCoder Python 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Microsoft WizardCoder Python 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-17
lastmod: 2023-08-17
draft: false
weight: 10
model_id: "microsoft-wizardcoder-python-34b"
vendor: "other"
version: "wizardcoder-python-34b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Microsoft WizardCoder Python 34B

## Przegląd modelu

Microsoft WizardCoder Python 34B 代码模型, 16K 上下文, 基于 Code Llama 34B, Python 代码生成突出。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | wizardcoder-python-34b | 2023-08-17 | 16K | text | text | Llama 2 Community License |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.0 | % | 5-shot |
| HumanEval | 79.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.7 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 67.2 | % | 3-shot CoT |
| GPQA | 36.6 | % | 0-shot |
| IFEval | 53.8 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 53.1 | % | 0-shot |
| WinoGrande | 70.4 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Przypadki użycia

- 代码生成与调试

## Referencje

- [Microsoft WizardCoder Python 34B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-08-17
- Dostawca: Other
