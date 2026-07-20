---
title: "DeepSeek V2 Chat: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek V2 Chat performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-17
lastmod: 2024-06-17
draft: false
weight: 10
model_id: "deepseek-v2-chat"
vendor: "deepseek"
version: "v2-chat"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2 Chat

## סקירת מודל

DeepSeek V2 Chat 对话版本, 32K 上下文, 针对对话场景优化, 适合聊天助手与客服应用。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2-chat | 2024-06-17 | 32K | text | text | DeepSeek License |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.4 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 38.3 | % | 0-shot |
| IFEval | 71.5 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 52.0 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

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

- 通用对话与问答

## הפניות

- [DeepSeek V2 Chat תיעוד](https://api-docs.deepseek.com/)
- תאריך שחרור: 2024-06-17
- ספק: Deepseek
