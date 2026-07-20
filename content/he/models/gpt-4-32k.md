---
title: "GPT-4 32K: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 32K performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-14
lastmod: 2023-03-14
draft: false
weight: 10
model_id: "gpt-4-32k"
vendor: "openai"
version: "4-32k"
tags: ["flagship", "long-context", "reasoning"]
---

# GPT-4 32K

## סקירת מודל

OpenAI GPT-4 32K 上下文版本, 支持 32768 token 长文本输入, 适合长文档理解与生成任务。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-32k | 2023-03-14 | 32K | text | text | Proprietary |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.8 | % | 5-shot |
| HumanEval | 76.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.6 | % | 0-shot CoT |
| MATH | 40.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.2 | % | 3-shot CoT |
| GPQA | 40.9 | % | 0-shot |
| IFEval | 74.7 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 54.9 | % | 0-shot |
| WinoGrande | 82.2 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 80.8, strong knowledge reasoning.
- 上下文窗口 32K，支持长文本。

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## הפניות

- [GPT-4 32K תיעוד](https://platform.openai.com/docs/models)
- תאריך שחרור: 2023-03-14
- ספק: Openai
