---
title: "Gemini 1.0 Flash: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Flash performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
model_id: "gemini-1-0-flash"
vendor: "google"
version: "1.0-flash"
tags: ["realtime", "legacy"]
---

# Gemini 1.0 Flash

## Обзор модели

Google Gemini 1.0 Flash 经济型, 32K 上下文, 速度快成本低, 适合实时多模态应用。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-flash | 2024-02-15 | 32K | text, image | text | Proprietary |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.7 | % | 5-shot |
| HumanEval | 65.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.2 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.8 | % | 3-shot CoT |
| GPQA | 37.7 | % | 0-shot |
| IFEval | 71.8 | % | prompt_strict |
| ARC | 92.6 | % | challenge |
| MUSR | 55.9 | % | 0-shot |
| WinoGrande | 80.1 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- GSM8K 86.2, robust math reasoning.

## Слабые стороны

- 闭源专有模型，不支持自托管。

## Сценарии

- 通用对话与问答

## Ссылки

- [Gemini 1.0 Flash Документация](https://ai.google.dev/gemini-api/docs)
- Дата выпуска: 2024-02-15
- Поставщик: Google
