---
title: "Code Llama 7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-7b"
vendor: "meta"
version: "code-llama-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 7B

## نظرة عامة على النموذج

Meta Code Llama 7B 代码专用开源模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-7b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.2 | % | 0-shot CoT |
| MATH | 47.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 29.5 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 76.3 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- MMLU 仅 58.5，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Code Llama 7B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2023-08-24
- المزود: Meta
