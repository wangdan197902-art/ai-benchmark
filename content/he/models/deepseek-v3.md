---
title: "DeepSeek V3: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek V3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-26
lastmod: 2024-12-26
draft: false
weight: 10
model_id: "deepseek-v3"
vendor: "deepseek"
version: "v3"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V3

## סקירת מודל

DeepSeek V3 是开源 MoE 架构模型，总参数 671B、活跃参数 37B，64K 上下文窗口，在 MMLU、HumanEval、MATH 等基准上达到闭源旗舰水平，价格仅为同级模型的 1/10。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v3 | 2024-12-26 | 64K | text | text | DeepSeek License |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.5 | % | 5-shot |
| HumanEval | 82.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.3 | % | 0-shot CoT |
| MATH | 61.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.9 | % | 3-shot CoT |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 88.5, strong knowledge reasoning.
- HumanEval 82.6, excellent code generation.
- GSM8K 89.3, robust math reasoning.
- 采用 MoE 混合专家架构。

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试

## הפניות

- [DeepSeek V3 תיעוד](https://api-docs.deepseek.com/)
- תאריך שחרור: 2024-12-26
- ספק: Deepseek
