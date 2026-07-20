---
title: "Gemma 2 27B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemma 2 27B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-27
lastmod: 2024-06-27
draft: false
weight: 10
model_id: "gemma-2-27b"
vendor: "google"
version: "gemma-2-27b"
tags: ["open-weights", "self-hostable"]
---

# Gemma 2 27B

## Model Genel Bakışı

Google Gemma 2 27B 开源模型, 8K 上下文, 在 27B 规模上接近 GPT-4 性能, 推理能力突出。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | gemma-2-27b | 2024-06-27 | 8K | text | text | Gemma License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.4 | % | 5-shot |
| HumanEval | 72.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.4 | % | 0-shot CoT |
| MATH | 35.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.2 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 72.5 | % | prompt_strict |
| ARC | 93.1 | % | challenge |
| MUSR | 53.0 | % | 0-shot |
| WinoGrande | 80.5 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [Gemma 2 27B Dokümantasyon](https://ai.google.dev/gemma/docs)
- Yayın Tarihi: 2024-06-27
- Satıcı: Google
