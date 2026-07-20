---
title: "Llama 2 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama 2 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-13b"
vendor: "meta"
version: "2-13b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 13B

## Panoramica del modello

Meta Llama 2 13B 中型开源模型, 4K 上下文, 13B 参数, 平衡性能与资源消耗, 适合中等规模部署。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-13b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 56.4 | % | 5-shot |
| HumanEval | 40.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 34.6 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.1 | % | 3-shot CoT |
| GPQA | 22.3 | % | 0-shot |
| IFEval | 49.9 | % | prompt_strict |
| ARC | 89.5 | % | challenge |
| MUSR | 33.8 | % | 0-shot |
| WinoGrande | 76.4 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- MMLU 仅 56.4，知识推理偏弱。
- HumanEval 40.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Llama 2 13B Documentazione](https://llama.meta.com/docs/)
- Data di rilascio: 2023-07-18
- Fornitore: Meta
