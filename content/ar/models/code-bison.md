---
title: "Code Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "code-bison"
vendor: "google"
version: "code-bison"
tags: ["coding", "legacy"]
---

# Code Bison

## نظرة عامة على النموذج

Google Vertex AI Code Bison 代码生成模型, 基于 PaLM 2, 8K 上下文, 支持多语言代码生成与补全。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | code-bison | 2023-05-10 | 8K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.0 | % | 5-shot |
| HumanEval | 76.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.0 | % | 0-shot CoT |
| MATH | 34.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 29.1 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 86.1 | % | challenge |
| MUSR | 49.8 | % | 0-shot |
| WinoGrande | 77.9 | % | 0-shot |

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

- [Code Bison الوثائق](https://ai.google.dev/gemini-api/docs)
- تاريخ الإصدار: 2023-05-10
- المزود: Google
