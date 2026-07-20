---
title: "DeepSeek Coder V2: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder V2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-21
lastmod: 2024-06-21
draft: false
weight: 10
model_id: "deepseek-coder-v2"
vendor: "deepseek"
version: "coder-v2"
tags: ["open-weights", "coding", "moe"]
---

# DeepSeek Coder V2

## Modellöversikt

DeepSeek Coder V2 代码专用 MoE 模型, 128K 上下文, 支持 338 种编程语言, 代码生成能力突出。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-v2 | 2024-06-21 | 128K | text | text | DeepSeek License |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.3 | % | 5-shot |
| HumanEval | 88.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.9 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 25.4 | % | 0-shot |
| IFEval | 56.7 | % | prompt_strict |
| ARC | 88.5 | % | challenge |
| MUSR | 40.3 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- HumanEval 88.9, excellent code generation.
- 采用 MoE 混合专家架构。

## Svagheter

- 闭源专有模型，不支持自托管。

## Användningsområden

- 代码生成与调试

## Referenser

- [DeepSeek Coder V2 Dokumentation](https://api-docs.deepseek.com/)
- Releasedatum: 2024-06-21
- Leverantör: Deepseek
