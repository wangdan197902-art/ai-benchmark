---
title: "Phi-3 Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-medium"
vendor: "other"
version: "phi-3-medium"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Medium

## Modellöversikt

Microsoft Phi-3 Medium 14B 模型, 4K 上下文 (可扩展 128K), 在 14B 规模上接近 GPT-3.5 性能。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-medium | 2024-05-21 | 4K | text | text | MIT |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.1 | % | 5-shot |
| HumanEval | 53.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.0 | % | 0-shot CoT |
| MATH | 34.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.4 | % | 3-shot CoT |
| GPQA | 25.6 | % | 0-shot |
| IFEval | 67.4 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 43.9 | % | 0-shot |
| WinoGrande | 72.1 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Användningsområden

- 通用对话与问答

## Referenser

- [Phi-3 Medium Dokumentation](https://huggingface.co/models)
- Releasedatum: 2024-05-21
- Leverantör: Other
