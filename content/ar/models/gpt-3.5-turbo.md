---
title: "GPT-3.5 Turbo: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-01
lastmod: 2023-03-01
draft: false
weight: 10
model_id: "gpt-3.5-turbo"
vendor: "openai"
version: "3.5-turbo"
tags: ["legacy", "realtime"]
---

# GPT-3.5 Turbo

## نظرة عامة على النموذج

OpenAI GPT-3.5 Turbo 经济型模型, 16K 上下文, 速度快价格低, 适合对话与通用任务。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo | 2023-03-01 | 16K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.1 | % | 5-shot |
| HumanEval | 51.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.3 | % | 0-shot CoT |
| MATH | 17.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 22.4 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 29.2 | % | 0-shot |
| WinoGrande | 76.7 | % | 0-shot |

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

- 通用对话与问答

## المراجع

- [GPT-3.5 Turbo الوثائق](https://platform.openai.com/docs/models)
- تاريخ الإصدار: 2023-03-01
- المزود: Openai
