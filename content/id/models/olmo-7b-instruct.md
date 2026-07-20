---
title: "OLMo 7B Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of OLMo 7B Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-01
lastmod: 2024-02-01
draft: false
weight: 10
model_id: "olmo-7b-instruct"
vendor: "other"
version: "olmo-7b-instruct"
tags: ["open-weights", "self-hostable"]
---

# OLMo 7B Instruct

## Ikhtisar Model

AllenAI OLMo 7B Instruct 指令微调版本, 2K 上下文, 改进指令遵循能力, 适合对话与助手场景。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | olmo-7b-instruct | 2024-02-01 | 2K | text | text | Apache 2.0 |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.6 | % | 5-shot |
| HumanEval | 50.5 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 58.7 | % | 0-shot CoT |
| MATH | 34.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.5 | % | 3-shot CoT |
| GPQA | 30.5 | % | 0-shot |
| IFEval | 63.6 | % | prompt_strict |
| ARC | 88.0 | % | challenge |
| MUSR | 42.5 | % | 0-shot |
| WinoGrande | 78.9 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- 可靠的通用模型。

## Kekurangan

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## Kasus Penggunaan

- 通用对话与问答

## Referensi

- [OLMo 7B Instruct Dokumentasi](https://huggingface.co/models)
- Tanggal Rilis: 2024-02-01
- Vendor: Other
