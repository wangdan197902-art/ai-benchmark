---
title: "Jamba Instruct: Complete Benchmark Performance Guide"
description: "In-depth analysis of Jamba Instruct performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-28
lastmod: 2024-03-28
draft: false
weight: 10
model_id: "jamba-instruct"
vendor: "other"
version: "jamba-instruct"
tags: ["open-weights", "long-context"]
---

# Jamba Instruct

## Model Genel Bakışı

AI21 Labs Jamba Instruct 指令微调模型, 256K 上下文, 首个商用 Mamba-Transformer 混合架构。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-instruct | 2024-03-28 | 256K | text | text | Jamba Open Model License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.2 | % | 5-shot |
| HumanEval | 66.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.2 | % | 0-shot CoT |
| MATH | 49.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 91.2 | % | challenge |
| MUSR | 56.9 | % | 0-shot |
| WinoGrande | 78.3 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 上下文窗口 256K，支持长文本。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 长文档摘要

## Referanslar

- [Jamba Instruct Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2024-03-28
- Satıcı: Other
