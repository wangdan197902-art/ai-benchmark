---
title: "Sonar Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Sonar Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "sonar-large"
vendor: "other"
version: "sonar-large"
tags: ["rag", "enterprise"]
---

# Sonar Large

## Ikhtisar Model

Perplexity Sonar Large 在线 RAG 模型, 128K 上下文, 基于 Llama 3 70B 微调, 集成实时搜索。

## Spesifikasi Inti

| Vendor | Versi | Tanggal Rilis | Jendela Konteks | Modalitas Input | Modalitas Output | Lisensi |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | sonar-large | 2024-05-13 | 128K | text | text | Proprietary |

## Kinerja Benchmark

| Benchmark | Skor | Satuan | Catatan |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.5 | % | 5-shot |
| HumanEval | 80.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 51.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.6 | % | 3-shot CoT |
| GPQA | 41.6 | % | 0-shot |
| IFEval | 74.9 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 65.6 | % | 0-shot |
| WinoGrande | 81.1 | % | 0-shot |

## Harga

| Input | Output | Baca Cache | Tulis Cache |
|------|--------|-----------|-----------|
| — | — | — | — |

*per juta token*

## Kelebihan

- MMLU score 82.5, strong knowledge reasoning.
- HumanEval 80.4, excellent code generation.
- 企业级合规认证。

## Kekurangan

- 闭源专有模型，不支持自托管。

## Kasus Penggunaan

- 代码生成与调试
- 企业客户支持

## Referensi

- [Sonar Large Dokumentasi](https://huggingface.co/models)
- Tanggal Rilis: 2024-05-13
- Vendor: Other
