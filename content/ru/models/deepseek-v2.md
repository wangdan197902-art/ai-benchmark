---
title: "DeepSeek V2: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek V2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
model_id: "deepseek-v2"
vendor: "deepseek"
version: "v2"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2

## Обзор модели

DeepSeek V2 开源 MoE 模型, 总参 236B/活跃 21B, 32K 上下文, 首创 MLA 注意力机制, 性价比突出。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2 | 2024-05-07 | 32K | text | text | DeepSeek License |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.2 | % | 5-shot |
| HumanEval | 75.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 35.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.5 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 78.6 | % | prompt_strict |
| ARC | 92.1 | % | challenge |
| MUSR | 53.4 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 采用 MoE 混合专家架构。

## Слабые стороны

- 闭源专有模型，不支持自托管。

## Сценарии

- 代码生成与调试

## Ссылки

- [DeepSeek V2 Документация](https://api-docs.deepseek.com/)
- Дата выпуска: 2024-05-07
- Поставщик: Deepseek
