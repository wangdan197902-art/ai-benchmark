---
title: "Gemini 1.5 Pro vs Gemini 1.5 Flash: Benchmark Comparison"
description: "Detailed comparison of Gemini 1.5 Pro and Gemini 1.5 Flash covering benchmarks, pricing, context window, and compliance."
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
comparison_id: "gemini-1-5-pro-vs-gemini-1-5-flash"
models: ["gemini-1-5-pro", "gemini-1-5-flash"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "google", "google"]
---

# Gemini 1.5 Pro против Gemini 1.5 Flash

## Обзор модели

Gemini 1.5 Pro and Gemini 1.5 Flash are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Ключевые характеристики

| Поставщик | Дата выпуска | Окно контекста | Лицензия |
|---------|-------------|----------------|---------|
| Google / Google | 2024-02-15 / 2024-05-14 | 2000K / 1000K | Proprietary / Proprietary |

## Производительность

| Бенчмарк | Gemini 1.5 Pro | Gemini 1.5 Flash | Победитель |
|------|------|------|--------|
| ARC | — | 93.4 | B |
| BBH (BIG-Bench Hard) | 84.0 | 71.7 | A |
| GPQA | — | 38.5 | B |
| GSM8K (Grade School Math 8K) | 91.7 | 75.2 | A |
| HumanEval | 71.9 | 67.5 | A |
| IFEval | — | 68.0 | B |
| MATH | 58.5 | 53.2 | A |
| MMLU (Massive Multitask Language Understanding) | 85.9 | 76.0 | A |
| MUSR | — | 46.1 | B |
| WinoGrande | — | 78.9 | B |

## Сравнение цен

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*за миллион токенов — A / B*

## Сильные стороны & Слабые стороны

### Gemini 1.5 Pro

- ✅ MMLU score 85.9, strong knowledge reasoning.
- ✅ GSM8K 91.7, robust math reasoning.
- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 2000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

### Gemini 1.5 Flash

- ✅ 支持文本、图像、音频多模态输入。
- ✅ 上下文窗口 1000K，支持长文本。
- ⚠️ 闭源专有模型，不支持自托管。

## Мнение редактора

Gemini 1.5 Pro and Gemini 1.5 Flash each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## ЧЗВ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Ссылки

- [Gemini 1.5 Pro Документация](https://ai.google.dev/gemini-api/docs)
- [Gemini 1.5 Flash Документация](https://ai.google.dev/gemini-api/docs)
