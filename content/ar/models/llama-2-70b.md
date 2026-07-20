---
title: "Llama 2 70B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 70B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-70b"
vendor: "meta"
version: "2-70b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 70B

## نظرة عامة على النموذج

Meta Llama 2 70B 开源模型, 4K 上下文, 在开源模型中领先, 商用许可, 适合企业自托管。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-70b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.0 | % | 5-shot |
| HumanEval | 50.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.8 | % | 0-shot CoT |
| MATH | 22.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.5 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 57.1 | % | prompt_strict |
| ARC | 80.3 | % | challenge |
| MUSR | 36.1 | % | 0-shot |
| WinoGrande | 73.4 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- MMLU 仅 53.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## حالات الاستخدام

- 通用对话与问答

## المراجع

- [Llama 2 70B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2023-07-18
- المزود: Meta
