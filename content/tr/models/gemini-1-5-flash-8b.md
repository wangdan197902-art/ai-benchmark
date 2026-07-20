---
title: "Gemini 1.5 Flash-8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash-8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-03
lastmod: 2024-10-03
draft: false
weight: 10
model_id: "gemini-1-5-flash-8b"
vendor: "google"
version: "1.5-flash-8b"
tags: ["multimodal", "realtime"]
---

# Gemini 1.5 Flash-8B

## Model Genel Bakışı

Google Gemini 1.5 Flash-8B 8B 参数经济型, 1M 上下文, 更低延迟, 适合高频实时多模态任务。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-8b | 2024-10-03 | 1000K | text, image, audio, video | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 35.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.8 | % | 3-shot CoT |
| GPQA | 35.0 | % | 0-shot |
| IFEval | 68.1 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 45.6 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 支持文本、图像、音频多模态输入。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试
- 视觉与图像理解

## Referanslar

- [Gemini 1.5 Flash-8B Dokümantasyon](https://ai.google.dev/gemini-api/docs)
- Yayın Tarihi: 2024-10-03
- Satıcı: Google
