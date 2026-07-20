---
title: "Claude 3.5 Haiku: Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3.5 Haiku performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-11-04
lastmod: 2024-11-04
draft: false
weight: 10
model_id: "claude-3-5-haiku"
vendor: "anthropic"
version: "3.5-haiku"
tags: ["realtime", "coding"]
---

# Claude 3.5 Haiku

## Model Genel Bakışı

Anthropic Claude 3.5 Haiku 经济型模型, 200K 上下文, 速度比 Sonnet 快 2 倍, 性能超越 Claude 3 Opus。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3.5-haiku | 2024-11-04 | 200K | text, image | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.6 | % | 5-shot |
| HumanEval | 73.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.5 | % | 0-shot CoT |
| MATH | 53.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 31.1 | % | 0-shot |
| IFEval | 73.6 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 52.3 | % | 0-shot |
| WinoGrande | 83.8 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [Claude 3.5 Haiku Dokümantasyon](https://docs.anthropic.com/claude/docs)
- Yayın Tarihi: 2024-11-04
- Satıcı: Anthropic
