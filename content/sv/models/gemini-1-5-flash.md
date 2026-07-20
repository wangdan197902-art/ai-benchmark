---
title: "Gemini 1.5 Flash: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-14
lastmod: 2024-05-14
draft: false
weight: 10
model_id: "gemini-1-5-flash"
vendor: "google"
version: "1.5-flash"
tags: ["multimodal", "realtime", "long-context"]
---

# Gemini 1.5 Flash

## Modellöversikt

Google Gemini 1.5 Flash 经济型模型, 1M 上下文, 速度快成本低, 适合大规模多模态任务。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash | 2024-05-14 | 1000K | text, image, audio, video | text | Proprietary |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.0 | % | 5-shot |
| HumanEval | 67.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.2 | % | 0-shot CoT |
| MATH | 53.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.7 | % | 3-shot CoT |
| GPQA | 38.5 | % | 0-shot |
| IFEval | 68.0 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 46.1 | % | 0-shot |
| WinoGrande | 78.9 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 支持文本、图像、音频多模态输入。
- 上下文窗口 1000K，支持长文本。

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 长文档摘要
- 视觉与图像理解

## Referenser

- [Gemini 1.5 Flash Dokumentation](https://ai.google.dev/gemini-api/docs)
- Releasedatum: 2024-05-14
- Leverantör: Google
