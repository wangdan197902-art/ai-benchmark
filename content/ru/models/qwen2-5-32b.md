---
title: "Qwen2.5 32B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 32B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-32b"
vendor: "alibaba"
version: "2.5-32b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2.5 32B

## Обзор модели

阿里巴巴 Qwen2.5 32B 开源中端模型, 131K 上下文, 性能接近 72B, 适合中等规模部署。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-32b | 2024-09-19 | 131K | text | text | Qwen License |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.5 | % | 5-shot |
| HumanEval | 68.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.3 | % | 0-shot CoT |
| MATH | 39.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.8 | % | 3-shot CoT |
| GPQA | 39.4 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 54.9 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 可靠的通用模型。

## Слабые стороны

- 闭源专有模型，不支持自托管。

## Сценарии

- 代码生成与调试

## Ссылки

- [Qwen2.5 32B Документация](https://qwenlm.github.io/)
- Дата выпуска: 2024-09-19
- Поставщик: Alibaba
