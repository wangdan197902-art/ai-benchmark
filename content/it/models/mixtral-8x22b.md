---
title: "Mixtral 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mixtral 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-10
lastmod: 2024-04-10
draft: false
weight: 10
model_id: "mixtral-8x22b"
vendor: "mistral"
version: "8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x22B

## Panoramica del modello

Mistral Mixtral 8x22B 是稀疏混合专家（MoE）开源模型，总参数 141B、活跃参数 39B，64K 上下文窗口，在多语言与代码任务上表现稳健，Apache 2.0 许可证可商用。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 8x22b | 2024-04-10 | 64K | text | text | Apache 2.0 |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.8 | % | 5-shot |
| HumanEval | 45.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.6 | % | 0-shot CoT |
| MATH | 46.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.5 | % | 3-shot CoT |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 采用 MoE 混合专家架构。

## Punti deboli

- HumanEval 45.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Mixtral 8x22B Documentazione](https://docs.mistral.ai/)
- Data di rilascio: 2024-04-10
- Fornitore: Mistral
