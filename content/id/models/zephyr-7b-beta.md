---
title: "Zephyr 7B Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Zephyr 7B Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-10-25
lastmod: 2023-10-25
draft: false
weight: 10
model_id: "zephyr-7b-beta"
vendor: "other"
version: "zephyr-7b-beta"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Zephyr 7B Beta

## Ikhtisar Model

HuggingFaceH4 Zephyr 7B Beta 对话模型, 4K 上下文, 基于 Mistral 7B DPO 微调, 性能接近 GPT-3.5。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-7b-beta | 2023-10-25 | 4K | text | text | MIT |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.1 | % | 5-shot |
| HumanEval | 38.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 50.4 | % | 0-shot CoT |
| MATH | 31.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.0 | % | 3-shot CoT |
| GPQA | 28.6 | % | 0-shot |
| IFEval | 51.2 | % | prompt_strict |
| ARC | 81.8 | % | challenge |
| MUSR | 32.6 | % | 0-shot |
| WinoGrande | 74.0 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 可靠的通用模型。

## Kekurangan

- HumanEval 38.4，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Kasus Penggunaan

- 通用对话与问答

## Referensi

- [Zephyr 7B Beta Dokumentasi](https://huggingface.co/models)
- Tanggal Rilis: 2023-10-25
- Vendor: Other
