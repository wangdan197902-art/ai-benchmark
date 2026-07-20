---
title: "Phi-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "phi-2"
vendor: "other"
version: "phi-2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-2

## Обзор модели

Microsoft Phi-2 2.7B 模型, 2K 上下文, 在 2.7B 规模上推理能力突出, 适合研究/教育用途。

## Основные характеристики

| Поставщик | Версия | Дата выпуска | Окно контекста | Входные модальности | Выходные модальности | Лицензия |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-2 | 2023-12-11 | 2K | text | text | MIT |

## Производительность

| Бенчмарк | Очки | Единица | Примечания |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.5 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.8 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.8 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 48.8 | % | prompt_strict |
| ARC | 75.1 | % | challenge |
| MUSR | 23.7 | % | 0-shot |
| WinoGrande | 72.8 | % | 0-shot |

## Цены

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — | — | — | — |

*за миллион токенов*

## Сильные стороны

- 可靠的通用模型。

## Слабые стороны

- MMLU 仅 57.5，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Сценарии

- 通用对话与问答

## Ссылки

- [Phi-2 Документация](https://huggingface.co/models)
- Дата выпуска: 2023-12-11
- Поставщик: Other
