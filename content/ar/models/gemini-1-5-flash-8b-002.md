---
title: "Gemini 1.5 Flash-8B 002: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash-8B 002 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-03
lastmod: 2024-10-03
draft: false
weight: 10
model_id: "gemini-1-5-flash-8b-002"
vendor: "google"
version: "1.5-flash-8b-002"
tags: ["multimodal", "realtime"]
---

# Gemini 1.5 Flash-8B 002

## نظرة عامة على النموذج

Google Gemini 1.5 Flash-8B 002 生产版本, 1M 上下文, 最低成本多模态推理。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-8b-002 | 2024-10-03 | 1000K | text, image, audio, video | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.5 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.3 | % | 0-shot CoT |
| MATH | 43.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.6 | % | 3-shot CoT |
| GPQA | 39.8 | % | 0-shot |
| IFEval | 74.3 | % | prompt_strict |
| ARC | 93.2 | % | challenge |
| MUSR | 54.7 | % | 0-shot |
| WinoGrande | 84.6 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- GSM8K 86.3, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## نقاط الضعف

- 闭源专有模型，不支持自托管。

## حالات الاستخدام

- 代码生成与调试
- 视觉与图像理解

## المراجع

- [Gemini 1.5 Flash-8B 002 الوثائق](https://ai.google.dev/gemini-api/docs)
- تاريخ الإصدار: 2024-10-03
- المزود: Google
