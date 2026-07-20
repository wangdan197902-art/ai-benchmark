---
title: "Nous Hermes 2 Yi 34B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Nous Hermes 2 Yi 34B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-01-22
lastmod: 2024-01-22
draft: false
weight: 10
model_id: "nous-hermes-2-yi-34b"
vendor: "other"
version: "nous-hermes-2-yi-34b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Nous Hermes 2 Yi 34B

## نظرة عامة على النموذج

NousResearch Hermes 2 Yi 34B 微调模型, 4K 上下文, 基于 Yi 34B, 改进多语言与指令遵循。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-yi-34b | 2024-01-22 | 4K | text | text | Apache 2.0 |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.9 | % | 5-shot |
| HumanEval | 73.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.7 | % | 0-shot CoT |
| MATH | 44.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.6 | % | 3-shot CoT |
| GPQA | 39.0 | % | 0-shot |
| IFEval | 68.3 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 48.8 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

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

- [Nous Hermes 2 Yi 34B الوثائق](https://huggingface.co/models)
- تاريخ الإصدار: 2024-01-22
- المزود: Other
