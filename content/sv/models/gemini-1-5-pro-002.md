---
title: "Gemini 1.5 Pro 002: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Pro 002 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-24
lastmod: 2024-09-24
draft: false
weight: 10
model_id: "gemini-1-5-pro-002"
vendor: "google"
version: "1.5-pro-002"
tags: ["flagship", "multimodal", "long-context"]
---

# Gemini 1.5 Pro 002

## Modellöversikt

Google Gemini 1.5 Pro 002 生产版本, 2M 上下文, 改进指令遵循与数学推理能力。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-pro-002 | 2024-09-24 | 2000K | text, image, audio, video | text | Proprietary |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.0 | % | 5-shot |
| HumanEval | 90.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 95.0 | % | 0-shot CoT |
| MATH | 55.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 87.2 | % | 3-shot CoT |
| GPQA | 56.5 | % | 0-shot |
| IFEval | 87.9 | % | prompt_strict |
| ARC | 95.9 | % | challenge |
| MUSR | 71.6 | % | 0-shot |
| WinoGrande | 85.8 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- MMLU score 87.0, strong knowledge reasoning.
- HumanEval 90.3, excellent code generation.
- GSM8K 95.0, robust math reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 2000K，支持长文本。

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## Referenser

- [Gemini 1.5 Pro 002 Dokumentation](https://ai.google.dev/gemini-api/docs)
- Releasedatum: 2024-09-24
- Leverantör: Google
