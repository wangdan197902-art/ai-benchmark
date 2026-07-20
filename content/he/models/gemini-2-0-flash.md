---
title: "Gemini 2.0 Flash: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 2.0 Flash performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-11
lastmod: 2024-12-11
draft: false
weight: 10
model_id: "gemini-2-0-flash"
vendor: "google"
version: "2.0-flash"
tags: ["flagship", "multimodal", "realtime"]
---

# Gemini 2.0 Flash

## סקירת מודל

Google Gemini 2.0 Flash 新一代模型, 1M 上下文, 原生工具调用与多模态输出, 性能超越 1.5 Pro。

## מפרט ליבה

| ספק | גרסה | תאריך שחרור | חלון הקשר | מודליות קלט | מודליות פלט | רישיון |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 2.0-flash | 2024-12-11 | 1048K | text, image, audio, video | text | Proprietary |

## ביצועי בנצ'מרק

| בנצ'מרק | ציון | יחידה | הערות |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.3 | % | 5-shot |
| HumanEval | 90.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 92.7 | % | 0-shot CoT |
| MATH | 71.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 55.0 | % | 0-shot |
| IFEval | 85.9 | % | prompt_strict |
| ARC | 95.7 | % | challenge |
| MUSR | 69.3 | % | 0-shot |
| WinoGrande | 89.5 | % | 0-shot |

## מחירים

| קלט | פלט | קריאת מטמון | כתיבת מטמון |
|------|--------|-----------|-----------|
| — | — | — | — |

*לכל מיליון טוקנים*

## חוזקות

- MMLU score 86.3, strong knowledge reasoning.
- HumanEval 90.7, excellent code generation.
- GSM8K 92.7, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## חולשות

- 闭源专有模型，不支持自托管。

## מקרי שימוש

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## הפניות

- [Gemini 2.0 Flash תיעוד](https://ai.google.dev/gemini-api/docs)
- תאריך שחרור: 2024-12-11
- ספק: Google
