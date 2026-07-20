---
title: "Mixtral 8x7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mixtral 8x7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mixtral-8x7b"
vendor: "mistral"
version: "8x7b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x7B

## סקירת מודל

Mistral Mixtral 8x7B 首个开源 MoE 模型, 总参 47B/活跃 13B, 32K 上下文, 性能接近 GPT-3.5。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 8x7b | 2023-12-11 | 32K | text | text | Apache 2.0 |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.2 | % | 5-shot |
| HumanEval | 79.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.7 | % | 0-shot CoT |
| MATH | 38.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.4 | % | 3-shot CoT |
| GPQA | 43.0 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 53.5 | % | 0-shot |
| WinoGrande | 82.0 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- 采用 MoE 混合专家架构。

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [Mixtral 8x7B תיעוד](https://docs.mistral.ai/)
- תאריך שחרור: 2023-12-11
- ספק: Mistral
