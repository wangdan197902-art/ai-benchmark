---
title: "Code Llama 13B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Code Llama 13B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-13b"
vendor: "meta"
version: "code-llama-13b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 13B

## Ikhtisar Model

Meta Code Llama 13B 代码专用开源模型, 16K 上下文, 13B 参数, 适合中等规模代码任务部署。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-13b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.9 | % | 5-shot |
| HumanEval | 69.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 55.9 | % | 0-shot CoT |
| MATH | 37.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.0 | % | 3-shot CoT |
| GPQA | 36.4 | % | 0-shot |
| IFEval | 50.1 | % | prompt_strict |
| ARC | 87.8 | % | challenge |
| MUSR | 47.3 | % | 0-shot |
| WinoGrande | 70.4 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 可靠的通用模型。

## Kekurangan

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Kasus Penggunaan

- 代码生成与调试

## Referensi

- [Code Llama 13B Dokumentasi](https://llama.meta.com/docs/)
- Tanggal Rilis: 2023-08-24
- Vendor: Meta
