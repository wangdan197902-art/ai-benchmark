---
title: "OLMo 7B SFT: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 7B SFT performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-01
lastmod: 2024-02-01
draft: false
weight: 10
model_id: "olmo-7b-sft"
vendor: "other"
version: "olmo-7b-sft"
tags: ["open-weights", "self-hostable"]
---

# OLMo 7B SFT

## Przegląd modelu

AllenAI OLMo 7B SFT 监督微调版本, 2K 上下文, 基于 Tulu 数据集微调, 适合通用对话任务。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-7b-sft | 2024-02-01 | 2K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.4 | % | 5-shot |
| HumanEval | 53.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.8 | % | 0-shot CoT |
| MATH | 43.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 64.0 | % | 3-shot CoT |
| GPQA | 31.8 | % | 0-shot |
| IFEval | 56.2 | % | prompt_strict |
| ARC | 89.3 | % | challenge |
| MUSR | 44.3 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [OLMo 7B SFT Dokumentacja](https://huggingface.co/models)
- Data wydania: 2024-02-01
- Dostawca: Other
