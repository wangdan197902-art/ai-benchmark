---
title: "Grok Vision Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok Vision Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-vision-beta"
vendor: "xai"
version: "vision-beta"
tags: ["multimodal", "legacy"]
---

# Grok Vision Beta

## Przegląd modelu

xAI Grok Vision Beta 早期多模态预览版, 8K 上下文, 支持图像理解, 集成 X 平台实时信息。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | vision-beta | 2023-11-04 | 8K | text, image | text | Proprietary |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.3 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 35.2 | % | 0-shot CoT |
| MATH | 24.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 56.8 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 46.8 | % | prompt_strict |
| ARC | 88.2 | % | challenge |
| MUSR | 44.5 | % | 0-shot |
| WinoGrande | 67.5 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- 支持文本、图像、音频多模态输入。

## Słabe strony

- HumanEval 44.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Przypadki użycia

- 视觉与图像理解

## Referencje

- [Grok Vision Beta Dokumentacja](https://docs.x.ai/)
- Data wydania: 2023-11-04
- Dostawca: Xai
