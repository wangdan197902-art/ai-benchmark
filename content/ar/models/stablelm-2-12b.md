---
title: "StableLM 2 12B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StableLM 2 12B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-19
lastmod: 2024-01-19
draft: false
weight: 10
model_id: "stablelm-2-12b"
vendor: "other"
version: "stablelm-2-12b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 2 12B

## نظرة عامة على النموذج

Stability AI StableLM 2 12B 模型, 4K 上下文, 多语言训练, 支持 7 种语言, 性能接近 Llama 2 13B。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-2-12b | 2024-01-19 | 4K | text | text | Stability AI Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.7 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.1 | % | 0-shot CoT |
| MATH | 37.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.6 | % | 3-shot CoT |
| GPQA | 44.0 | % | 0-shot |
| IFEval | 80.0 | % | prompt_strict |
| ARC | 94.9 | % | challenge |
| MUSR | 58.1 | % | 0-shot |
| WinoGrande | 84.1 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [StableLM 2 12B الوثائق](https://huggingface.co/models)
- تاريخ الإصدار: 2024-01-19
- المزود: Other
