---
title: "StarCoder2 15B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarCoder2 15B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-15b"
vendor: "other"
version: "starcoder2-15b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 15B

## Ikhtisar Model

BigCode StarCoder2 15B 代码专用开源模型, 16K 上下文, 训练于 80+ 编程语言, 代码生成能力突出。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-15b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.6 | % | 5-shot |
| HumanEval | 73.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.6 | % | 0-shot CoT |
| MATH | 46.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.8 | % | 3-shot CoT |
| GPQA | 35.3 | % | 0-shot |
| IFEval | 59.6 | % | prompt_strict |
| ARC | 87.6 | % | challenge |
| MUSR | 51.7 | % | 0-shot |
| WinoGrande | 70.2 | % | 0-shot |

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

- [StarCoder2 15B Dokumentasi](https://huggingface.co/models)
- Tanggal Rilis: 2024-02-28
- Vendor: Other
