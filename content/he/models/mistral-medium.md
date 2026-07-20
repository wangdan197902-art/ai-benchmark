---
title: "Mistral Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mistral-medium"
vendor: "mistral"
version: "medium"
tags: ["eu-residency"]
---

# Mistral Medium

## סקירת מודל

Mistral AI Medium 中端模型, 32K 上下文, 平衡性能与成本, 适合企业级通用任务。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | medium | 2023-12-11 | 32K | text | text | Apache 2.0 |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.9 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 54.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 48.7 | % | 0-shot |
| IFEval | 77.4 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 82.4 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 82.9, strong knowledge reasoning.

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [Mistral Medium תיעוד](https://docs.mistral.ai/)
- תאריך שחרור: 2023-12-11
- ספק: Mistral
