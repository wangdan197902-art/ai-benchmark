---
title: "Qwen2 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-7b"
vendor: "alibaba"
version: "2-7b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2 7B

## Обзор модели

阿里巴巴 Qwen2 7B 经济型开源模型, 131K 上下文, 7B 参数, 性能超越 Llama 2 13B, 适合本地部署。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-7b | 2024-06-07 | 131K | text | text | Qwen License |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 73.2 | % | 0-shot CoT |
| MATH | 40.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.3 | % | 3-shot CoT |
| GPQA | 31.6 | % | 0-shot |
| IFEval | 61.8 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 43.9 | % | 0-shot |
| WinoGrande | 77.3 | % | 0-shot |

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

- 通用对话与问答

## Ссылки

- [Qwen2 7B Документация](https://qwenlm.github.io/)
- Дата выпуска: 2024-06-07
- Поставщик: Alibaba
