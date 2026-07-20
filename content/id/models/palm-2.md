---
title: "PaLM 2: Complete Benchmark Performance Guide"
description: "In-depth analysis of PaLM 2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "palm-2"
vendor: "google"
version: "palm-2"
tags: ["legacy"]
---

# PaLM 2

## Ikhtisar Model

Google PaLM 2 大型语言模型, 8K 上下文, 改进多语言/推理/编码能力, Bard 初始版本所用模型。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | palm-2 | 2023-05-10 | 8K | text | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.4 | % | 5-shot |
| HumanEval | 44.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 49.0 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.9 | % | 3-shot CoT |
| GPQA | 20.3 | % | 0-shot |
| IFEval | 44.7 | % | prompt_strict |
| ARC | 89.2 | % | challenge |
| MUSR | 29.3 | % | 0-shot |
| WinoGrande | 68.6 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 可靠的通用模型。

## Kekurangan

- HumanEval 44.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Kasus Penggunaan

- 通用对话与问答

## Referensi

- [PaLM 2 Dokumentasi](https://ai.google.dev/gemini-api/docs)
- Tanggal Rilis: 2023-05-10
- Vendor: Google
