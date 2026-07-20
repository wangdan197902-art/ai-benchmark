---
title: "MPT 30B: Complete Benchmark Performance Guide"
description: "In-depth analysis of MPT 30B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-22
lastmod: 2023-06-22
draft: false
weight: 10
model_id: "mpt-30b"
vendor: "other"
version: "mpt-30b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# MPT 30B

## Przegląd modelu

MosaicML MPT 30B 开源模型, 8K 上下文, 300 亿参数, 改进长上下文处理, Apache 2.0 可商用。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | mpt-30b | 2023-06-22 | 8K | text | text | Apache 2.0 |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.2 | % | 5-shot |
| HumanEval | 49.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 21.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 24.2 | % | 0-shot |
| IFEval | 51.2 | % | prompt_strict |
| ARC | 80.7 | % | challenge |
| MUSR | 28.9 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 可靠的通用模型。

## Słabe strony

- MMLU 仅 55.2，知识推理偏弱。
- HumanEval 49.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Przypadki użycia

- 通用对话与问答

## Referencje

- [MPT 30B Dokumentacja](https://huggingface.co/models)
- Data wydania: 2023-06-22
- Dostawca: Other
