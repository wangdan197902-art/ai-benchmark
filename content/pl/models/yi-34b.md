---
title: "Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
model_id: "yi-34b"
vendor: "other"
version: "yi-34b"
tags: ["open-weights", "chinese", "self-hostable", "legacy"]
---

# Yi 34B

## Przegląd modelu

01.AI Yi 34B 首代开源模型, 4K 上下文, 340 亿参数, 在开源模型中曾排名第一。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-34b | 2023-11-05 | 4K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.5 | % | 5-shot |
| HumanEval | 35.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.3 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.8 | % | 3-shot CoT |
| GPQA | 20.6 | % | 0-shot |
| IFEval | 48.2 | % | prompt_strict |
| ARC | 87.2 | % | challenge |
| MUSR | 36.8 | % | 0-shot |
| WinoGrande | 71.5 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- MMLU 仅 55.5，知识推理偏弱。
- HumanEval 35.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [Yi 34B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-11-05
- Dostawca: Other
