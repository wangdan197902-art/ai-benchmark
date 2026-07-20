---
title: "Qwen2.5 32B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 32B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-32b"
vendor: "alibaba"
version: "2.5-32b"
tags: ["open-weights", "chinese", "coding"]
---

# Qwen2.5 32B

## Ikhtisar Model

阿里巴巴 Qwen2.5 32B 开源中端模型, 131K 上下文, 性能接近 72B, 适合中等规模部署。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-32b | 2024-09-19 | 131K | text | text | Qwen License |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.5 | % | 5-shot |
| HumanEval | 68.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 76.3 | % | 0-shot CoT |
| MATH | 39.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.8 | % | 3-shot CoT |
| GPQA | 39.4 | % | 0-shot |
| IFEval | 73.5 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 54.9 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

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

- 代码生成与调试

## Referensi

- [Qwen2.5 32B Dokumentasi](https://qwenlm.github.io/)
- Tanggal Rilis: 2024-09-19
- Vendor: Alibaba
