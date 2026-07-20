---
title: "Open-Platypus: Complete Benchmark Performance Guide"
description: "In-depth analysis of Open-Platypus performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-15
lastmod: 2023-09-15
draft: false
weight: 10
model_id: "open-platypus"
vendor: "other"
version: "open-platypus"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Open-Platypus

## Обзор модели

Garage bAInd Open-Platypus 数据集与模型, 2K 上下文, 基于 Llama 2 微调, 适合 STEM 推理任务。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | open-platypus | 2023-09-15 | 2K | text | text | MIT |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.7 | % | 5-shot |
| HumanEval | 48.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.9 | % | 0-shot CoT |
| MATH | 21.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.7 | % | 3-shot CoT |
| GPQA | 34.9 | % | 0-shot |
| IFEval | 46.0 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 40.0 | % | 0-shot |
| WinoGrande | 66.7 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 可靠的通用模型。

## Слабые стороны

- HumanEval 48.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Сценарии

- 通用对话与问答

## Ссылки

- [Open-Platypus Документация](https://huggingface.co/models)
- Дата выпуска: 2023-09-15
- Поставщик: Other
