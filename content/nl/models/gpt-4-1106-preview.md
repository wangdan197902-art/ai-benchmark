---
title: "GPT-4 1106 Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 1106 Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-1106-preview"
vendor: "openai"
version: "4-1106-preview"
tags: ["flagship", "long-context", "tool-use"]
---

# GPT-4 1106 Preview

## Modeloverzicht

OpenAI GPT-4 1106 预览版, 128K 上下文, 改进函数调用与 JSON 模式, 适合结构化输出任务。

## Kernspecificaties

| Leverancier | Versie | Releasedatum | Contextvenster | Invoermodaliteiten | Uitvoermodaliteiten | Licentie |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-1106-preview | 2023-11-06 | 128K | text | text | Proprietary |

## Benchmarkprestaties

| Benchmark | Score | Eenheid | Notities |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.8 | % | 5-shot |
| HumanEval | 83.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.4 | % | 0-shot CoT |
| MATH | 52.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 36.2 | % | 0-shot |
| IFEval | 73.9 | % | prompt_strict |
| ARC | 94.3 | % | challenge |
| MUSR | 58.4 | % | 0-shot |
| WinoGrande | 82.0 | % | 0-shot |

## Prijzen

| Invoer | Uitvoer | Cache-lezen | Cache-schrijven |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljoen tokens*

## Sterktes

- MMLU score 81.8, strong knowledge reasoning.
- HumanEval 83.7, excellent code generation.
- GSM8K 85.4, robust math reasoning.
- 上下文窗口 128K，支持长文本。

## Zwaktes

- 闭源专有模型，不支持自托管。

## Gebruiksscenario's

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## Referenties

- [GPT-4 1106 Preview Documentatie](https://platform.openai.com/docs/models)
- Releasedatum: 2023-11-06
- Leverancier: Openai
