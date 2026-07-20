---
title: "Code Llama 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-34b"
vendor: "meta"
version: "code-llama-34b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 34B

## نظرة عامة على النموذج

Meta Code Llama 34B 代码专用开源模型, 16K 上下文, 中等规模, 平衡代码生成性能与资源消耗。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-34b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 74.5 | % | 5-shot |
| HumanEval | 71.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.8 | % | 0-shot CoT |
| MATH | 44.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 59.1 | % | 3-shot CoT |
| GPQA | 27.0 | % | 0-shot |
| IFEval | 58.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 44.9 | % | 0-shot |
| WinoGrande | 80.0 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Code Llama 34B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2023-08-24
- المزود: Meta
