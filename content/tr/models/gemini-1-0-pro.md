---
title: "Gemini 1.0 Pro: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Pro performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-pro"
vendor: "google"
version: "1.0-pro"
tags: ["legacy"]
---

# Gemini 1.0 Pro

## Model Genel Bakışı

Google Gemini 1.0 Pro 首代模型, 32K 上下文, 在 MMLU/GSM8K 上超越 GPT-3.5, 多模态能力初步集成。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-pro | 2023-12-06 | 32K | text | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.4 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.1 | % | 3-shot CoT |
| GPQA | 47.7 | % | 0-shot |
| IFEval | 75.1 | % | prompt_strict |
| ARC | 94.1 | % | challenge |
| MUSR | 57.8 | % | 0-shot |
| WinoGrande | 84.5 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 84.5, strong knowledge reasoning.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [Gemini 1.0 Pro Dokümantasyon](https://ai.google.dev/gemini-api/docs)
- Yayın Tarihi: 2023-12-06
- Satıcı: Google
