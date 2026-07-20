---
title: "Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-405b"
vendor: "meta"
version: "3.1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Llama 3.1 405B

## نظرة عامة على النموذج

Meta Llama 3.1 405B 是当前最大规模的开源权重模型之一，拥有 4050 亿参数，128K 上下文窗口，在 MMLU、HumanEval、MATH 等基准上接近闭源旗舰水平，支持自托管部署。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-405b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.9 | % | 3-shot CoT |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- MMLU score 88.6, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 89.2, robust math reasoning.

## نقاط الضعف

- 闭源专有模型，不支持自托管。

## حالات الاستخدام

- 代码生成与调试

## المراجع

- [Llama 3.1 405B الوثائق](https://llama.meta.com/docs/)
- تاريخ الإصدار: 2024-07-23
- المزود: Meta
