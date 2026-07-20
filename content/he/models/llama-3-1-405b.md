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

## סקירת מודל

Meta Llama 3.1 405B 是当前最大规模的开源权重模型之一，拥有 4050 亿参数，128K 上下文窗口，在 MMLU、HumanEval、MATH 等基准上接近闭源旗舰水平，支持自托管部署。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-405b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.9 | % | 3-shot CoT |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 88.6, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 89.2, robust math reasoning.

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [Llama 3.1 405B תיעוד](https://llama.meta.com/docs/)
- תאריך שחרור: 2024-07-23
- ספק: Meta
