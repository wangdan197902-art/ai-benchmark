---
title: "Qwen2.5 0.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 0.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-0-5b"
vendor: "alibaba"
version: "2.5-0-5b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2.5 0.5B

## Modellöversikt

阿里巴巴 Qwen2.5 0.5B 超小型开源模型, 32K 上下文, 0.5B 参数, 适合极低资源环境与移动端。

## Kärnspecifikationer

| Leverantör | Version | Releasedatum | Kontextfönster | Inmatningsmodaliteter | Utmatningsmodaliteter | Licens |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-0-5b | 2024-09-19 | 32K | text | text | Qwen License |

## Benchmarkprestanda

| Benchmark | Poäng | Enhet | Anteckningar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 41.5 | % | 5-shot |
| HumanEval | 31.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.2 | % | 0-shot CoT |
| MATH | 15.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.0 | % | 3-shot CoT |
| GPQA | 23.2 | % | 0-shot |
| IFEval | 48.5 | % | prompt_strict |
| ARC | 85.4 | % | challenge |
| MUSR | 28.9 | % | 0-shot |
| WinoGrande | 64.3 | % | 0-shot |

## Priser

| Inmatning | Utmatning | Cacheläsning | Cacheskrivning |
|------|--------|-----------|-----------|
| — | — | — | — |

*per miljon tokens*

## Styrkor

- 可靠的通用模型。

## Svagheter

- MMLU 仅 41.5，知识推理偏弱。
- HumanEval 31.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Användningsområden

- 通用对话与问答

## Referenser

- [Qwen2.5 0.5B Dokumentation](https://qwenlm.github.io/)
- Releasedatum: 2024-09-19
- Leverantör: Alibaba
