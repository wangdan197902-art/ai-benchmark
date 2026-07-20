---
title: "Codestral: Complete Benchmark Performance Guide"
description: "In-depth analysis of Codestral performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-29
lastmod: 2024-05-29
draft: false
weight: 10
model_id: "codestral"
vendor: "mistral"
version: "codestral"
tags: ["coding", "open-weights"]
---

# Codestral

## סקירת מודל

Mistral Codestral 22B 代码专用模型, 32K 上下文, 支持 80+ 编程语言, 代码生成与补全性能突出。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral | 2024-05-29 | 32K | text | text | MNPL |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.1 | % | 5-shot |
| HumanEval | 69.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.3 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.3 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 59.4 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.2 | % | 0-shot |
| WinoGrande | 75.8 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- 可靠的通用模型。

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [Codestral תיעוד](https://docs.mistral.ai/)
- תאריך שחרור: 2024-05-29
- ספק: Mistral
