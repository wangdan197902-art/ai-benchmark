---
title: "Gemma 2 27B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2 27B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-27
lastmod: 2024-06-27
draft: false
weight: 10
model_id: "gemma-2-27b"
vendor: "google"
version: "gemma-2-27b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2 27B

## نظرة عامة على النموذج

Google Gemma 2 27B 开源模型, 8K 上下文, 在 27B 规模上接近 GPT-4 性能, 推理能力突出。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2-27b | 2024-06-27 | 8K | text | text | Gemma License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.4 | % | 5-shot |
| HumanEval | 72.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.4 | % | 0-shot CoT |
| MATH | 35.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.2 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 72.5 | % | prompt_strict |
| ARC | 93.1 | % | challenge |
| MUSR | 53.0 | % | 0-shot |
| WinoGrande | 80.5 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Gemma 2 27B الوثائق](https://ai.google.dev/gemma/docs)
- تاريخ الإصدار: 2024-06-27
- المزود: Google
