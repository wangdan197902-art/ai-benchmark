---
title: "DBRX Instruct vs Mixtral 8x22B: Benchmark Comparison"
description: "Detailed comparison of DBRX Instruct and Mixtral 8x22B covering benchmarks, pricing, context window, and compliance."
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
comparison_id: "dbrx-instruct-vs-mixtral-8x22b"
models: ["dbrx-instruct", "mixtral-8x22b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "mistral"]
---

# DBRX Instruct против Mixtral 8x22B

## Обзор модели

DBRX Instruct and Mixtral 8x22B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Ключевые характеристики

| Поставщик | Дата выпуска | Окно контекста | Лицензия |
|---------|-------------|----------------|---------|
| Other / Mistral | 2024-03-27 / 2024-04-10 | 32K / 64K | DBRX Open Model License / Apache 2.0 |

## Производительность

| Бенчмарк | DBRX Instruct | Mixtral 8x22B | Победитель |
|------|------|------|--------|
| ARC | 93.9 | — | A |
| BBH (BIG-Bench Hard) | 71.7 | 74.5 | B |
| GPQA | 34.7 | — | A |
| GSM8K (Grade School Math 8K) | 78.7 | 78.6 | Tie |
| HumanEval | 72.8 | 45.2 | A |
| IFEval | 73.1 | — | A |
| MATH | 50.1 | 46.0 | A |
| MMLU (Massive Multitask Language Understanding) | 81.3 | 77.8 | A |
| MUSR | 54.7 | — | A |
| WinoGrande | 81.8 | — | A |

## Сравнение цен

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*за миллион токенов — A / B*

## Сильные стороны & Слабые стороны

### DBRX Instruct

- ✅ MMLU score 81.3, strong knowledge reasoning.
- ✅ 采用 MoE 混合专家架构。
- ⚠️ 闭源专有模型，不支持自托管。

### Mixtral 8x22B

- ✅ 采用 MoE 混合专家架构。
- ⚠️ HumanEval 45.2，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。

## Мнение редактора

DBRX Instruct and Mixtral 8x22B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## ЧЗВ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Ссылки

- [DBRX Instruct Документация](https://huggingface.co/models)
- [Mixtral 8x22B Документация](https://docs.mistral.ai/)
