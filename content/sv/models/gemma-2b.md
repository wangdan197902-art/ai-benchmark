---
title: "Gemma 2B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-21
lastmod: 2024-02-21
draft: false
weight: 10
model_id: "gemma-2b"
vendor: "google"
version: "gemma-2b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2B

## Modellöversikt

Google Gemma 2B 轻量开源模型, 8K 上下文, 2B 参数, 适合资源受限环境与边缘部署。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2b | 2024-02-21 | 8K | text | text | Gemma License |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 48.0 | % | 5-shot |
| HumanEval | 43.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 27.8 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 53.0 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 46.4 | % | prompt_strict |
| ARC | 77.7 | % | challenge |
| MUSR | 30.6 | % | 0-shot |
| WinoGrande | 72.0 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- MMLU 仅 48.0，知识推理偏弱。
- HumanEval 43.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Användningsområden

- 通用对话与问答

## Referenser

- [Gemma 2B Dokumentation](https://ai.google.dev/gemma/docs)
- Releasedatum: 2024-02-21
- Leverantör: Google
