---
title: "Claude Instant 1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude Instant 1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "claude-instant-1"
vendor: "anthropic"
version: "instant-1"
tags: ["legacy"]
---

# Claude Instant 1

## نظرة عامة على النموذج

Anthropic Claude Instant 1 轻量快速模型, 9K 上下文, 价格仅为 Claude 1 的 1/5, 适合实时对话。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | instant-1 | 2023-03-14 | 9K | text | text | Proprietary |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.1 | % | 5-shot |
| HumanEval | 28.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.0 | % | 0-shot CoT |
| MATH | 22.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.1 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 53.2 | % | prompt_strict |
| ARC | 80.9 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 77.2 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 可靠的通用模型。

## نقاط الضعف

- MMLU 仅 57.1，知识推理偏弱。
- HumanEval 28.5，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 9K 偏小。

## حالات الاستخدام

- 通用对话与问答

## المراجع

- [Claude Instant 1 الوثائق](https://docs.anthropic.com/claude/docs)
- تاريخ الإصدار: 2023-03-14
- المزود: Anthropic
