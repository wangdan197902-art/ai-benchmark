---
title: "Hermes 3 Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-405b"
vendor: "other"
version: "hermes-3-llama-3-1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Hermes 3 Llama 3.1 405B

## Panoramica del modello

NousResearch Hermes 3 Llama 3.1 405B 微调模型, 131K 上下文, 改进中立性与推理, 性能超越基座模型。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-405b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.9 | % | 0-shot CoT |
| MATH | 65.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 78.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 86.5 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 83.9, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 88.9, robust math reasoning.

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试

## Riferimenti

- [Hermes 3 Llama 3.1 405B Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-08-12
- Fornitore: Other
