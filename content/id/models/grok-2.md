---
title: "Grok-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2"
vendor: "xai"
version: "2"
tags: ["flagship", "multimodal", "realtime"]
---

# Grok-2

## Ikhtisar Model

xAI Grok-2 是 xAI 旗舰模型，131K 上下文窗口，支持文本与图像输入，在 MMLU、HumanEval、MATH 等基准上接近头部闭源模型，集成于 X 平台提供实时信息。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2 | 2024-08-13 | 131K | text, image | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 87.5 | % | 5-shot |
| HumanEval | 88.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 93.2 | % | 0-shot CoT |
| MATH | 76.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.0 | % | 3-shot CoT |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- MMLU score 87.5, strong knowledge reasoning.
- HumanEval 88.4, excellent code generation.
- GSM8K 93.2, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Referensi

- [Grok-2 Dokumentasi](https://docs.x.ai/)
- Tanggal Rilis: 2024-08-13
- Vendor: Xai
