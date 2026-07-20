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

## Model Genel Bakışı

01.AI Yi Vision 多模态模型, 16K 上下文, 支持图像理解, 中英文视觉问答能力突出。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-vision | 2024-05-13 | 16K | text, image | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
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

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 85.5, strong knowledge reasoning.
- GSM8K 89.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Kullanım Senaryoları

- 代码生成与调试
- 视觉与图像理解

## Referanslar

- [Yi Vision Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2024-05-13
- Satıcı: Other
