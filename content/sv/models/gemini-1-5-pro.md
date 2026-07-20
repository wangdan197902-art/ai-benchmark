---
title: "Gemini 1.5 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Pro performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
model_id: "gemini-1-5-pro"
vendor: "google"
version: "1.5-pro"
tags: ["flagship", "multimodal", "long-context"]
---

# Gemini 1.5 Pro

## Modellöversikt

Google DeepMind Gemini 1.5 Pro 模型，2M 上下文窗口（业界领先），支持文本、图像、音频、视频多模态输入，长文档理解能力突出。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-pro | 2024-02-15 | 2000K | text, image, audio, video | text | Proprietary |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.9 | % | 5-shot |
| HumanEval | 71.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.7 | % | 0-shot CoT |
| MATH | 58.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.0 | % | 3-shot CoT |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- MMLU score 85.9, strong knowledge reasoning.
- GSM8K 91.7, robust math reasoning.
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

- [Gemini 1.5 Pro Dokumentation](https://ai.google.dev/gemini-api/docs)
- Releasedatum: 2024-02-15
- Leverantör: Google
