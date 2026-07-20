---
title: "Mistral 7B v0.2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-23
lastmod: 2024-03-23
draft: false
weight: 10
model_id: "mistral-7b-v0.2"
vendor: "mistral"
version: "7b-v0.2"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.2

## Ikhtisar Model

Mistral 7B v0.2 开源模型, 32K 上下文, 扩展上下文窗口, 改进推理, 适合通用任务。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.2 | 2024-03-23 | 32K | text | text | Apache 2.0 |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.4 | % | 5-shot |
| HumanEval | 59.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.2 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 36.7 | % | 0-shot |
| WinoGrande | 71.7 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 可靠的通用模型。

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 通用对话与问答

## Referensi

- [Mistral 7B v0.2 Dokumentasi](https://docs.mistral.ai/)
- Tanggal Rilis: 2024-03-23
- Vendor: Mistral
