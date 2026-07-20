---
title: "Yi Large vs Yi 34B: Benchmark Comparison"
description: "Detailed comparison of Yi Large and Yi 34B covering benchmarks, pricing, context window, and compliance."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
comparison_id: "yi-large-vs-yi-34b"
models: ["yi-large", "yi-34b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Yi Large против Yi 34B

## Обзор модели

Yi Large and Yi 34B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Ключевые характеристики

| Поставщик | Дата выпуска | Окно контекста | Лицензия |
|---------|-------------|----------------|---------|
| Other / Other | 2024-05-13 / 2023-11-05 | 32K / 4K | Proprietary / Apache 2.0 |

## Производительность

| Бенчмарк | Yi Large | Yi 34B | Победитель |
|------|------|------|--------|
| ARC | 94.8 | 87.2 | A |
| BBH (BIG-Bench Hard) | 77.1 | 48.8 | A |
| GPQA | 35.2 | 20.6 | A |
| GSM8K (Grade School Math 8K) | 81.3 | 48.3 | A |
| HumanEval | 72.2 | 35.8 | A |
| IFEval | 73.4 | 48.2 | A |
| MATH | 55.9 | 20.5 | A |
| MMLU (Massive Multitask Language Understanding) | 82.8 | 55.5 | A |
| MUSR | 59.4 | 36.8 | A |
| WinoGrande | 84.1 | 71.5 | A |

## Сравнение цен

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*за миллион токенов — A / B*

## Сильные стороны & Слабые стороны

### Yi Large

- ✅ MMLU score 82.8, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Yi 34B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 55.5，知识推理偏弱。
- ⚠️ HumanEval 35.8，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## Мнение редактора

Yi Large and Yi 34B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## ЧЗВ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Ссылки

- [Yi Large Документация](https://huggingface.co/models)
- [Yi 34B Документация](https://huggingface.co/models)
