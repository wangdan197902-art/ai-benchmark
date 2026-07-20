---
title: "Gemma 2B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-21
lastmod: 2024-02-21
draft: false
weight: 10
model_id: "gemma-2b"
vendor: "google"
version: "gemma-2b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2B

## نظرة عامة على النموذج

Google Gemma 2B 轻量开源模型, 8K 上下文, 2B 参数, 适合资源受限环境与边缘部署。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2b | 2024-02-21 | 8K | text | text | Gemma License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 48.0 | % | 5-shot |
| HumanEval | 43.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 27.8 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 46.4 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 30.6 | % | 0-shot |
| WinoGrande | 72.0 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- MMLU 仅 48.0，知识推理偏弱。
- HumanEval 43.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## حالات الاستخدام

- 通用对话与问答

## المراجع

- [Gemma 2B الوثائق](https://ai.google.dev/gemma/docs)
- تاريخ الإصدار: 2024-02-21
- المزود: Google
