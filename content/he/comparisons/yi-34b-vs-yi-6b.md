---
title: "Yi 34B vs Yi 6B: Benchmark Comparison"
description: "Detailed comparison of Yi 34B and Yi 6B covering benchmarks, pricing, context window, and compliance."
date: 2023-11-05
lastmod: 2023-11-05
draft: false
weight: 10
comparison_id: "yi-34b-vs-yi-6b"
models: ["yi-34b", "yi-6b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "other", "other"]
---

# Yi 34B נגד Yi 6B

## סקירת מודל

Yi 34B and Yi 6B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## מפרט עיקרי

| ספק | תאריך שחרור | חלון הקשר | רישיון |
|---------|-------------|----------------|---------|
| Other / Other | 2023-11-05 / 2023-11-05 | 4K / 4K | Apache 2.0 / Apache 2.0 |

## ביצועי בנצ'מרק

| בנצ'מרק | Yi 34B | Yi 6B | זוכה |
|------|------|------|--------|
| ARC | 87.2 | 88.4 | B |
| BBH (BIG-Bench Hard) | 48.8 | 55.3 | B |
| GPQA | 20.6 | 26.3 | B |
| GSM8K (Grade School Math 8K) | 48.3 | 37.0 | A |
| HumanEval | 35.8 | 42.3 | B |
| IFEval | 48.2 | 54.9 | B |
| MATH | 20.5 | 29.9 | B |
| MMLU (Massive Multitask Language Understanding) | 55.5 | 68.0 | B |
| MUSR | 36.8 | 29.5 | A |
| WinoGrande | 71.5 | 72.2 | B |

## השוואת מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*לכל מיליון טוקנים — A / B*

## חוזקות & חולשות

### Yi 34B

- ✅ 可靠的通用模型。
- ⚠️ MMLU 仅 55.5，知识推理偏弱。
- ⚠️ HumanEval 35.8，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

### Yi 6B

- ✅ 可靠的通用模型。
- ⚠️ HumanEval 42.3，代码能力较弱。
- ⚠️ 闭源专有模型，不支持自托管。
- ⚠️ 上下文窗口 4K 偏小。

## דעת העורך

Yi 34B and Yi 6B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## שאלות נפוצות

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## הפניות

- [Yi 34B תיעוד](https://huggingface.co/models)
- [Yi 6B תיעוד](https://huggingface.co/models)
