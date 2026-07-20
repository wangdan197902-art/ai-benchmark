---
title: "Qwen2 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-72b"
vendor: "alibaba"
version: "2-72b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2 72B

## סקירת מודל

阿里巴巴 Qwen2 72B 开源旗舰, 131K 上下文, 多语言/数学/编程能力突出, 性能接近 GPT-4。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-72b | 2024-06-07 | 131K | text | text | Qwen License |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.2 | % | 5-shot |
| HumanEval | 76.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 87.0 | % | 0-shot CoT |
| MATH | 71.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 53.6 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 94.4 | % | challenge |
| MUSR | 68.9 | % | 0-shot |
| WinoGrande | 82.5 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 80.2, strong knowledge reasoning.
- GSM8K 87.0, robust math reasoning.

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [Qwen2 72B תיעוד](https://qwenlm.github.io/)
- תאריך שחרור: 2024-06-07
- ספק: Alibaba
