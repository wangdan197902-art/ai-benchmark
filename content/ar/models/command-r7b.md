---
title: "Command R7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Command R7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r7b"
vendor: "cohere"
version: "r7b"
tags: ["open-weights", "rag", "self-hostable"]
---

# Command R7B

## نظرة عامة على النموذج

Cohere Command R7B 轻量开源模型, 128K 上下文, 7B 参数, 为 RAG 与工具调用优化, 适合边缘部署。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r7b | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.1 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 67.2 | % | prompt_strict |
| ARC | 90.7 | % | challenge |
| MUSR | 47.0 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

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

- [Command R7B الوثائق](https://docs.cohere.com/docs)
- تاريخ الإصدار: 2024-08-13
- المزود: Cohere
