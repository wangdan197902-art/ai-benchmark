---
title: "Sonar Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "sonar-small"
vendor: "other"
version: "sonar-small"
tags: ["rag", "realtime"]
---

# Sonar Small

## סקירת מודל

Perplexity Sonar Small 经济型在线 RAG 模型, 128K 上下文, 基于 Llama 3 8B 微调, 速度快成本低。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-small | 2024-05-13 | 128K | text | text | Proprietary |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.0 | % | 5-shot |
| HumanEval | 72.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.2 | % | 0-shot CoT |
| MATH | 43.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 34.5 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 91.7 | % | challenge |
| MUSR | 47.6 | % | 0-shot |
| WinoGrande | 81.4 | % | 0-shot |

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

- 代码生成与调试

## הפניות

- [Sonar Small תיעוד](https://huggingface.co/models)
- תאריך שחרור: 2024-05-13
- ספק: Other
