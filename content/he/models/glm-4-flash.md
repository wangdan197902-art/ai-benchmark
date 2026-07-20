---
title: "GLM-4 Flash: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Flash performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-flash"
vendor: "other"
version: "glm-4-flash"
tags: ["chinese", "realtime"]
---

# GLM-4 Flash

## סקירת מודל

清华智谱 GLM-4 Flash 免费模型, 131K 上下文, 速度最快, 适合高并发实时场景。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-flash | 2024-08-12 | 131K | text | text | Proprietary |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.0 | % | 5-shot |
| HumanEval | 67.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.4 | % | 0-shot CoT |
| MATH | 39.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.5 | % | 3-shot CoT |
| GPQA | 31.3 | % | 0-shot |
| IFEval | 65.9 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 56.0 | % | 0-shot |
| WinoGrande | 81.1 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 80.0, strong knowledge reasoning.

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 通用对话与问答

## הפניות

- [GLM-4 Flash תיעוד](https://huggingface.co/models)
- תאריך שחרור: 2024-08-12
- ספק: Other
