---
title: "GPT-4o mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4o mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
model_id: "gpt-4o-mini"
vendor: "openai"
version: "4o-mini"
tags: ["multimodal", "realtime"]
---

# GPT-4o mini

## Обзор модели

OpenAI 经济型多模态模型, 128K 上下文, 支持文本与图像输入, 平衡成本与性能, 适合大规模部署。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4o-mini | 2024-07-18 | 128K | text, image | text | Proprietary |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.7 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.1 | % | 0-shot CoT |
| MATH | 51.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 67.9 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 53.1 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 支持文本、图像、音频多模态输入。

## Слабые стороны

- 闭源专有模型，不支持自托管。

## Сценарии

- 代码生成与调试
- 视觉与图像理解

## Ссылки

- [GPT-4o mini Документация](https://platform.openai.com/docs/models)
- Дата выпуска: 2024-07-18
- Поставщик: Openai
