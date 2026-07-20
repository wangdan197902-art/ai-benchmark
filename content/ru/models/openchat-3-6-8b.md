---
title: "OpenChat 3.6 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of OpenChat 3.6 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "openchat-3-6-8b"
vendor: "other"
version: "openchat-3-6-8b"
tags: ["open-weights", "self-hostable"]
---

# OpenChat 3.6 8B

## Обзор модели

OpenChat 3.6 8B 对话模型, 8K 上下文, 基于 Llama 3 8B 微调, 改进推理与编码能力。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | openchat-3-6-8b | 2024-05-21 | 8K | text | text | Apache 2.0 |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 69.2 | % | 5-shot |
| HumanEval | 61.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.8 | % | 0-shot CoT |
| MATH | 33.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.0 | % | 3-shot CoT |
| GPQA | 30.3 | % | 0-shot |
| IFEval | 56.7 | % | prompt_strict |
| ARC | 89.2 | % | challenge |
| MUSR | 38.2 | % | 0-shot |
| WinoGrande | 74.5 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 可靠的通用模型。

## Слабые стороны

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Сценарии

- 通用对话与问答

## Ссылки

- [OpenChat 3.6 8B Документация](https://huggingface.co/models)
- Дата выпуска: 2024-05-21
- Поставщик: Other
