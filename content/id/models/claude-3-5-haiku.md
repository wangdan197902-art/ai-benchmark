---
title: "Claude 3.5 Haiku: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Haiku performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-11-04
lastmod: 2024-11-04
draft: false
weight: 10
model_id: "claude-3-5-haiku"
vendor: "anthropic"
version: "3.5-haiku"
tags: ["realtime", "coding"]
---

# Claude 3.5 Haiku

## Ikhtisar Model

Anthropic Claude 3.5 Haiku 经济型模型, 200K 上下文, 速度比 Sonnet 快 2 倍, 性能超越 Claude 3 Opus。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-haiku | 2024-11-04 | 200K | text, image | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.6 | % | 5-shot |
| HumanEval | 73.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 53.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 31.1 | % | 0-shot |
| IFEval | 73.6 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 52.3 | % | 0-shot |
| WinoGrande | 83.8 | % | 0-shot |

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

- [Claude 3.5 Haiku Dokumentasi](https://docs.anthropic.com/claude/docs)
- Tanggal Rilis: 2024-11-04
- Vendor: Anthropic
