---
title: "Mistral 7B v0.3: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral 7B v0.3 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-22
lastmod: 2024-05-22
draft: false
weight: 10
model_id: "mistral-7b-v0.3"
vendor: "mistral"
version: "7b-v0.3"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.3

## Model Genel Bakışı

Mistral 7B v0.3 开源模型, 32K 上下文, 改进 v0.2, 扩展词汇表至 32768, 适合本地部署。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.3 | 2024-05-22 | 32K | text | text | Apache 2.0 |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.6 | % | 5-shot |
| HumanEval | 68.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.4 | % | 0-shot CoT |
| MATH | 26.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 31.2 | % | 0-shot |
| IFEval | 60.9 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

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

- 通用对话与问答

## Referanslar

- [Mistral 7B v0.3 Dokümantasyon](https://docs.mistral.ai/)
- Yayın Tarihi: 2024-05-22
- Satıcı: Mistral
