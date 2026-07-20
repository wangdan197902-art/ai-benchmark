---
title: "Phi-3 Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-medium"
vendor: "other"
version: "phi-3-medium"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Medium

## Обзор модели

Microsoft Phi-3 Medium 14B 模型, 4K 上下文 (可扩展 128K), 在 14B 规模上接近 GPT-3.5 性能。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-medium | 2024-05-21 | 4K | text | text | MIT |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.1 | % | 5-shot |
| HumanEval | 53.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.0 | % | 0-shot CoT |
| MATH | 34.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 25.6 | % | 0-shot |
| IFEval | 67.4 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 43.9 | % | 0-shot |
| WinoGrande | 72.1 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 可靠的通用模型。

## Слабые стороны

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Сценарии

- 通用对话与问答

## Ссылки

- [Phi-3 Medium Документация](https://huggingface.co/models)
- Дата выпуска: 2024-05-21
- Поставщик: Other
