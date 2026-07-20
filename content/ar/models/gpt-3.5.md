---
title: "GPT-3.5: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-3.5 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2022-11-30
lastmod: 2022-11-30
draft: false
weight: 10
model_id: "gpt-3.5"
vendor: "openai"
version: "3.5"
tags: ["legacy"]
---

# GPT-3.5

## نظرة عامة على النموذج

OpenAI GPT-3.5 基础模型, 4K 上下文, ChatGPT 初始版本所用模型, 推理能力优于 GPT-3。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 3.5 | 2022-11-30 | 4K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.3 | % | 5-shot |
| HumanEval | 28.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.6 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.9 | % | 3-shot CoT |
| GPQA | 26.9 | % | 0-shot |
| IFEval | 52.8 | % | prompt_strict |
| ARC | 81.8 | % | challenge |
| MUSR | 40.4 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- MMLU 仅 50.3，知识推理偏弱。
- HumanEval 28.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## حالات الاستخدام

- 通用对话与问答

## المراجع

- [GPT-3.5 الوثائق](https://platform.openai.com/docs/models)
- تاريخ الإصدار: 2022-11-30
- المزود: Openai
