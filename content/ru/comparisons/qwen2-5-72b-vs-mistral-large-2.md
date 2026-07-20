---
title: "Qwen2.5 72B vs Mistral Large 2: Benchmark Comparison"
description: "Detailed comparison of Qwen2.5 72B and Mistral Large 2 covering benchmarks, pricing, context window, and compliance."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
comparison_id: "qwen2-5-72b-vs-mistral-large-2"
models: ["qwen2-5-72b", "mistral-large-2"]
benchmarks: ["bbh", "gsm8k", "humaneval", "math", "mmlu"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "mistral"]
---

# Qwen2.5 72B против Mistral Large 2

## Обзор модели

Qwen2.5 72B and Mistral Large 2 are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## Ключевые характеристики

| Поставщик | Дата выпуска | Окно контекста | Лицензия |
|---------|-------------|----------------|---------|
| Alibaba / Mistral | 2024-09-19 / 2024-07-24 | 131K / 128K | Qwen License / Mistral Research License |

## Производительность

| Бенчмарк | Qwen2.5 72B | Mistral Large 2 | Победитель |
|------|------|------|--------|
| BBH (BIG-Bench Hard) | 82.4 | 81.0 | A |
| GSM8K (Grade School Math 8K) | 88.4 | 93.0 | B |
| HumanEval | 86.6 | 92.0 | B |
| MATH | 83.1 | 71.0 | A |
| MMLU (Massive Multitask Language Understanding) | 86.1 | 84.0 | A |

## Сравнение цен

| Вход | Выход | Чтение кэша | Запись кэша |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*за миллион токенов — A / B*

## Сильные стороны & Слабые стороны

### Qwen2.5 72B

- ✅ MMLU score 86.1, strong knowledge reasoning.
- ✅ HumanEval 86.6, excellent code generation.
- ✅ GSM8K 88.4, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Mistral Large 2

- ✅ MMLU score 84.0, strong knowledge reasoning.
- ✅ HumanEval 92.0, excellent code generation.
- ✅ GSM8K 93.0, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## Мнение редактора

Qwen2.5 72B and Mistral Large 2 each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## ЧЗВ

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## Ссылки

- [Qwen2.5 72B Документация](https://qwenlm.github.io/)
- [Mistral Large 2 Документация](https://docs.mistral.ai/)
