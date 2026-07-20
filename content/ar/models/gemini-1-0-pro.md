---
title: "Gemini 1.0 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Pro performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-pro"
vendor: "google"
version: "1.0-pro"
tags: ["legacy"]
---

# Gemini 1.0 Pro

## نظرة عامة على النموذج

Google Gemini 1.0 Pro 首代模型, 32K 上下文, 在 MMLU/GSM8K 上超越 GPT-3.5, 多模态能力初步集成。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-pro | 2023-12-06 | 32K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.4 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.1 | % | 3-shot CoT |
| GPQA | 47.7 | % | 0-shot |
| IFEval | 75.1 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 57.8 | % | 0-shot |
| WinoGrande | 84.5 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- MMLU score 84.5, strong knowledge reasoning.

## نقاط الضعف

- 闭源专有模型，不支持自托管。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Gemini 1.0 Pro الوثائق](https://ai.google.dev/gemini-api/docs)
- تاريخ الإصدار: 2023-12-06
- المزود: Google
