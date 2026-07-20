---
title: "GLM-4V 9B: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4V 9B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-05
lastmod: 2024-06-05
draft: false
weight: 10
model_id: "glm-4v-9b"
vendor: "other"
version: "glm-4v-9b"
tags: ["open-weights", "chinese", "self-hostable", "multimodal"]
---

# GLM-4V 9B

## نظرة عامة على النموذج

清华智谱 GLM-4V 9B 多模态开源模型, 131K 上下文, 9B 参数, 视觉理解能力突出。

## المواصفات الأساسية

| المزود | الإصدار | تاريخ الإصدار | نافذة السياق | وسائط الإدخال | وسائط الإخراج | الترخيص |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4v-9b | 2024-06-05 | 131K | text, image | text | GLM-4 License |

## أداء المعايير

| المعيار | النتيجة | الوحدة | ملاحظات |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.4 | % | 5-shot |
| HumanEval | 66.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 73.5 | % | 0-shot CoT |
| MATH | 33.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.1 | % | 3-shot CoT |
| GPQA | 28.3 | % | 0-shot |
| IFEval | 67.4 | % | prompt_strict |
| ARC | 90.2 | % | challenge |
| MUSR | 38.5 | % | 0-shot |
| WinoGrande | 73.1 | % | 0-shot |

## التسعير

| الإدخال | الإخراج | قراءة الذاكرة المؤقتة | كتابة الذاكرة المؤقتة |
|------|--------|-----------|-----------|
| — | — | — | — |

*لكل مليون رمز*

## نقاط القوة

- 支持文本、图像、音频多模态输入。

## نقاط الضعف

- 闭源专有模型，不支持自托管。

## حالات الاستخدام

- 视觉与图像理解

## المراجع

- [GLM-4V 9B الوثائق](https://huggingface.co/models)
- تاريخ الإصدار: 2024-06-05
- المزود: Other
