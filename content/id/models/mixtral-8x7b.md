---
title: "Mixtral 8x7B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mixtral 8x7B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mixtral-8x7b"
vendor: "mistral"
version: "8x7b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x7B

## Ikhtisar Model

Mistral Mixtral 8x7B 首个开源 MoE 模型, 总参 47B/活跃 13B, 32K 上下文, 性能接近 GPT-3.5。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 8x7b | 2023-12-11 | 32K | text | text | Apache 2.0 |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.2 | % | 5-shot |
| HumanEval | 79.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 79.7 | % | 0-shot CoT |
| MATH | 38.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.4 | % | 3-shot CoT |
| GPQA | 43.0 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 91.6 | % | challenge |
| MUSR | 53.5 | % | 0-shot |
| WinoGrande | 82.0 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 采用 MoE 混合专家架构。

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 代码生成与调试

## Referensi

- [Mixtral 8x7B Dokumentasi](https://docs.mistral.ai/)
- Tanggal Rilis: 2023-12-11
- Vendor: Mistral
