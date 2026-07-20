---
title: "GPT-3.5 Turbo 16K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 Turbo 16K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-06-13
lastmod: 2023-06-13
draft: false
weight: 10
model_id: "gpt-3.5-turbo-16k"
vendor: "openai"
version: "3.5-turbo-16k"
tags: ["legacy", "long-context"]
---

# GPT-3.5 Turbo 16K

## نظرة عامة على النموذج

OpenAI GPT-3.5 Turbo 16K 长上下文版本, 支持 16385 token, 适合中等长度文档处理。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5-turbo-16k | 2023-06-13 | 16K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.2 | % | 5-shot |
| HumanEval | 36.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.8 | % | 0-shot CoT |
| MATH | 30.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 21.6 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 83.1 | % | challenge |
| MUSR | 29.1 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 上下文窗口 16K，支持长文本。

## نقاط الضعف

- HumanEval 36.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## حالات الاستخدام

- 长文档摘要

## المراجع

- [GPT-3.5 Turbo 16K الوثائق](https://platform.openai.com/docs/models)
- تاريخ الإصدار: 2023-06-13
- المزود: Openai
