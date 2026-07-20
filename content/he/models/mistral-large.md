---
title: "Mistral Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-large"
vendor: "mistral"
version: "large"
tags: ["flagship", "eu-residency"]
---

# Mistral Large

## סקירת מודל

Mistral AI Large 首代旗舰, 32K 上下文, 多语言与推理能力突出, 原生支持函数调用与 JSON 输出。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large | 2024-02-26 | 32K | text | text | Apache 2.0 |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.0 | % | 5-shot |
| HumanEval | 73.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.7 | % | 3-shot CoT |
| GPQA | 38.1 | % | 0-shot |
| IFEval | 75.8 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 52.1 | % | 0-shot |
| WinoGrande | 83.3 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 82.0, strong knowledge reasoning.

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试
- Agent 工作流与工具调用

## הפניות

- [Mistral Large תיעוד](https://docs.mistral.ai/)
- תאריך שחרור: 2024-02-26
- ספק: Mistral
