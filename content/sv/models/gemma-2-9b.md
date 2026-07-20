---
title: "Gemma 2 9B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2 9B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-27
lastmod: 2024-06-27
draft: false
weight: 10
model_id: "gemma-2-9b"
vendor: "google"
version: "gemma-2-9b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2 9B

## Modellöversikt

Google Gemma 2 9B 开源模型, 8K 上下文, 在 9B 规模上超越 Llama 3 8B, 推理能力接近 70B 模型。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2-9b | 2024-06-27 | 8K | text | text | Gemma License |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.3 | % | 5-shot |
| HumanEval | 60.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 64.3 | % | 0-shot CoT |
| MATH | 28.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.7 | % | 3-shot CoT |
| GPQA | 30.3 | % | 0-shot |
| IFEval | 64.3 | % | prompt_strict |
| ARC | 90.3 | % | challenge |
| MUSR | 44.1 | % | 0-shot |
| WinoGrande | 72.5 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Användningsområden

- 通用对话与问答

## Referenser

- [Gemma 2 9B Dokumentation](https://ai.google.dev/gemma/docs)
- Releasedatum: 2024-06-27
- Leverantör: Google
