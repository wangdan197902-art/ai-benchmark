---
title: "Hermes 3 Llama 3.1 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-8b"
vendor: "other"
version: "hermes-3-llama-3-1-8b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 8B

## نظرة عامة على النموذج

NousResearch Hermes 3 Llama 3.1 8B 微调模型, 131K 上下文, 经济型开源模型, 适合本地部署。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-8b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.1 | % | 5-shot |
| HumanEval | 67.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 72.9 | % | 0-shot CoT |
| MATH | 25.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.6 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 60.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 38.0 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

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

- 通用对话与问答

## المراجع

- [Hermes 3 Llama 3.1 8B الوثائق](https://huggingface.co/models)
- تاريخ الإصدار: 2024-08-12
- المزود: Other
