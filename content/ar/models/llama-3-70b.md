---
title: "Llama 3 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-3-70b"
vendor: "meta"
version: "3-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3 70B

## نظرة عامة على النموذج

Meta Llama 3 70B 中端开源模型, 8K 上下文, 在 MMLU/HumanEval 上接近 GPT-4, 开源旗舰之一。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3-70b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 73.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.2 | % | 0-shot CoT |
| MATH | 50.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.6 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 72.2 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.2 | % | 0-shot |
| WinoGrande | 79.2 | % | 0-shot |

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

- [Llama 3 70B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2024-04-18
- المزود: Meta
