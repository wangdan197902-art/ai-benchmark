---
title: "Mistral Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-large"
vendor: "mistral"
version: "large"
tags: ["flagship", "eu-residency"]
---

# Mistral Large

## Ikhtisar Model

Mistral AI Large 首代旗舰, 32K 上下文, 多语言与推理能力突出, 原生支持函数调用与 JSON 输出。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large | 2024-02-26 | 32K | text | text | Apache 2.0 |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.0 | % | 5-shot |
| HumanEval | 73.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.7 | % | 3-shot CoT |
| GPQA | 38.1 | % | 0-shot |
| IFEval | 75.8 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 52.1 | % | 0-shot |
| WinoGrande | 83.3 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- MMLU score 82.0, strong knowledge reasoning.

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 代码生成与调试
- Agent 工作流与工具调用

## Referensi

- [Mistral Large Dokumentasi](https://docs.mistral.ai/)
- Tanggal Rilis: 2024-02-26
- Vendor: Mistral
