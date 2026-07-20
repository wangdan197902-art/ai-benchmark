---
title: "Claude 3 Opus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-04
lastmod: 2024-03-04
draft: false
weight: 10
model_id: "claude-3-opus"
vendor: "anthropic"
version: "3-opus"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus

## Przegląd modelu

Anthropic Claude 3 Opus 旗舰模型, 200K 上下文, 超越 GPT-4 的推理与创意能力, 适合复杂分析任务。

## Podstawowe specyfikacje

| Dostawca | Wersja | Data wydania | Okno kontekstowe | Modalności wejściowe | Modalności wyjściowe | Licencja |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus | 2024-03-04 | 200K | text, image | text | Proprietary |

## Wydajność benchmarków

| Benchmark | Wynik | Jednostka | Uwagi |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.2 | % | 5-shot |
| HumanEval | 83.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.8 | % | 0-shot CoT |
| MATH | 42.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 46.0 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 53.3 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## Ceny

| Wejście | Wyjście | Odczyt pamięci podręcznej | Zapis pamięci podręcznej |
|------|--------|-----------|-----------|
| — | — | — | — |

*za milion tokenów*

## Mocne strony

- MMLU score 81.2, strong knowledge reasoning.
- HumanEval 83.3, excellent code generation.
- GSM8K 91.8, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## Słabe strony

- 闭源专有模型，不支持自托管。

## Przypadki użycia

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## Referencje

- [Claude 3 Opus Dokumentacja](https://docs.anthropic.com/claude/docs)
- Data wydania: 2024-03-04
- Dostawca: Anthropic
