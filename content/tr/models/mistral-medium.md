---
title: "Mistral Medium: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Medium performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "mistral-medium"
vendor: "mistral"
version: "medium"
tags: ["eu-residency"]
---

# Mistral Medium

## Model Genel Bakışı

Mistral AI Medium 中端模型, 32K 上下文, 平衡性能与成本, 适合企业级通用任务。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | medium | 2023-12-11 | 32K | text | text | Apache 2.0 |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.9 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 54.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.4 | % | 3-shot CoT |
| GPQA | 48.7 | % | 0-shot |
| IFEval | 77.4 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 82.4 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 82.9, strong knowledge reasoning.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [Mistral Medium Dokümantasyon](https://docs.mistral.ai/)
- Yayın Tarihi: 2023-12-11
- Satıcı: Mistral
