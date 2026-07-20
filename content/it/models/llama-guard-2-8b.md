---
title: "Llama Guard 2 8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Llama Guard 2 8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-18
lastmod: 2024-04-18
draft: false
weight: 10
model_id: "llama-guard-2-8b"
vendor: "meta"
version: "guard-2-8b"
tags: ["open-weights", "self-hostable"]
---

# Llama Guard 2 8B

## Panoramica del modello

Meta Llama Guard 2 8B 内容安全分类模型, 8K 上下文, 用于检测输入输出中的有害内容。

## Specifiche principali

| Fornitore | Versione | Data di rilascio | Finestra di contesto | Modalità di input | Modalità di output | Licenza |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | guard-2-8b | 2024-04-18 | 8K | text | text | Llama 3 Community License |

## Prestazioni benchmark

| Benchmark | Punteggio | Unità | Note |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 26.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 46.3 | % | 0-shot CoT |
| MATH | 26.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.6 | % | 3-shot CoT |
| GPQA | 18.0 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 76.3 | % | challenge |
| MUSR | 34.9 | % | 0-shot |
| WinoGrande | 66.5 | % | 0-shot |

## Prezzi

| Input | Output | Lettura cache | Scrittura cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per milione di token*

## Punti di forza

- 可靠的通用模型。

## Punti deboli

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 26.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Casi d'uso

- 通用对话与问答

## Riferimenti

- [Llama Guard 2 8B Documentazione](https://llama.meta.com/docs/)
- Data di rilascio: 2024-04-18
- Fornitore: Meta
