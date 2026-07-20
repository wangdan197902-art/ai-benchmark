---
title: "Sonar Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "sonar-large"
vendor: "other"
version: "sonar-large"
tags: ["rag", "enterprise"]
---

# Sonar Large

## Panoramica del modello

Perplexity Sonar Large 在线 RAG 模型, 128K 上下文, 基于 Llama 3 70B 微调, 集成实时搜索。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-large | 2024-05-13 | 128K | text | text | Proprietary |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.5 | % | 5-shot |
| HumanEval | 80.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 51.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 41.6 | % | 0-shot |
| IFEval | 74.9 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 65.6 | % | 0-shot |
| WinoGrande | 81.1 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- MMLU score 82.5, strong knowledge reasoning.
- HumanEval 80.4, excellent code generation.
- 企业级合规认证。

## Punti deboli

- 闭源专有模型，不支持自托管。

## Casi d'uso

- 代码生成与调试
- 企业客户支持

## Riferimenti

- [Sonar Large Documentazione](https://huggingface.co/models)
- Data di rilascio: 2024-05-13
- Fornitore: Other
