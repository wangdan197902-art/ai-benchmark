---
title: "Qwen1.5 72B vs Qwen2 72B: Benchmark Comparison"
description: "Detailed comparison of Qwen1.5 72B and Qwen2 72B covering benchmarks, pricing, context window, and compliance."
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
comparison_id: "qwen1-5-72b-vs-qwen2-72b"
models: ["qwen1-5-72b", "qwen2-72b"]
benchmarks: ["arc", "bbh", "gpqa", "gsm8k", "humaneval", "ifeval", "math", "mmlu", "musr", "winogrande"]
verdict: "See Editor's Take section."
tags: ["comparison", "alibaba", "alibaba"]
---

# Qwen1.5 72B ضد Qwen2 72B

## نظرة عامة على النموذج

Qwen1.5 72B and Qwen2 72B are both notable options in the AI model market. This page compares their benchmarks, pricing, and compliance.

## المواصفات الرئيسية

| المزود | تاريخ الإصدار | نافذة السياق | الترخيص |
|---------|-------------|----------------|---------|
| Alibaba / Alibaba | 2024-02-25 / 2024-06-07 | 32K / 131K | Qwen License / Qwen License |

## أداء المعايير

| المعيار | Qwen1.5 72B | Qwen2 72B | الفائز |
|------|------|------|--------|
| ARC | 92.6 | 94.4 | B |
| BBH (BIG-Bench Hard) | 76.5 | 83.4 | B |
| GPQA | 39.8 | 53.6 | B |
| GSM8K (Grade School Math 8K) | 80.9 | 87.0 | B |
| HumanEval | 65.2 | 76.5 | B |
| IFEval | 76.4 | 76.9 | B |
| MATH | 37.6 | 71.9 | B |
| MMLU (Massive Multitask Language Understanding) | 81.3 | 80.2 | A |
| MUSR | 50.8 | 68.9 | B |
| WinoGrande | 83.1 | 82.5 | A |

## مقارنة الأسعار

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — / — | — / — | — / — | — / — |

*لكل مليون رمز — A / B*

## نقاط القوة & نقاط الضعف

### Qwen1.5 72B

- ✅ MMLU score 81.3, strong knowledge reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

### Qwen2 72B

- ✅ MMLU score 80.2, strong knowledge reasoning.
- ✅ GSM8K 87.0, robust math reasoning.
- ⚠️ 闭源专有模型，不支持自托管。

## رأي المحرر

Qwen1.5 72B and Qwen2 72B each have their strengths. Choose based on workload (code, long context, vision), referencing the tables above.

## الأسئلة الشائعة

### Which model is better for coding tasks?
Refer to the HumanEval benchmark table; the model with a higher score is better suited for coding tasks.

### Which model is cheaper?
Refer to the pricing comparison table above; the model with lower input/output prices is more cost-effective.

### Which has a longer context window?
Refer to the key specifications table; the model with a larger context window is better for long documents.

## المراجع

- [Qwen1.5 72B الوثائق](https://qwenlm.github.io/)
- [Qwen2 72B الوثائق](https://qwenlm.github.io/)
