---
title: "DBRX Base: Complete Benchmark Performance Guide"
description: "In-depth analysis of DBRX Base performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-27
lastmod: 2024-03-27
draft: false
weight: 10
model_id: "dbrx-base"
vendor: "other"
version: "dbrx-base"
tags: ["open-weights", "moe", "self-hostable"]
---

# DBRX Base

## Panoramica del modello

Databricks DBRX Base 基础 MoE 模型, 32K 上下文, 总参 132B/活跃 36B, 适合企业定制微调。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | dbrx-base | 2024-03-27 | 32K | text | text | DBRX Open Model License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.9 | % | 5-shot |
| HumanEval | 72.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.4 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 39.3 | % | 0-shot |
| IFEval | 79.3 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 53.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 采用 MoE 混合专家架构。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试

## Riferimenti

- [DBRX Base Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-03-27
- Fornitore: Other
