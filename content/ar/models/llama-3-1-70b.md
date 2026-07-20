---
title: "Llama 3.1 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-70b"
vendor: "meta"
version: "3.1-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.1 70B

## نظرة عامة على النموذج

Meta Llama 3.1 70B 中端开源模型, 128K 上下文, 性能接近 GPT-4, 推理与编码能力突出。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-70b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.6 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 38.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 40.0 | % | 0-shot |
| IFEval | 73.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 81.0 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- 闭源专有模型，不支持自托管。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Llama 3.1 70B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2024-07-23
- المزود: Meta
