---
title: "Yi Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "yi-vision"
vendor: "other"
version: "yi-vision"
tags: ["multimodal", "chinese"]
---

# Yi Vision

## Ikhtisar Model

01.AI Yi Vision 多模态模型, 16K 上下文, 支持图像理解, 中英文视觉问答能力突出。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-vision | 2024-05-13 | 16K | text, image | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.5 | % | 5-shot |
| HumanEval | 76.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 89.9 | % | 0-shot CoT |
| MATH | 58.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.3 | % | 3-shot CoT |
| GPQA | 50.3 | % | 0-shot |
| IFEval | 81.4 | % | prompt_strict |
| ARC | 95.1 | % | challenge |
| MUSR | 61.4 | % | 0-shot |
| WinoGrande | 82.3 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- MMLU score 85.5, strong knowledge reasoning.
- GSM8K 89.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Kekurangan

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Kasus Penggunaan

- 代码生成与调试
- 视觉与图像理解

## Referensi

- [Yi Vision Dokumentasi](https://huggingface.co/models)
- Tanggal Rilis: 2024-05-13
- Vendor: Other
