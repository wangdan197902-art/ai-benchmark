---
title: "Qwen1.5 72B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen1.5 72B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-72b"
vendor: "alibaba"
version: "1.5-72b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 72B

## Model Genel Bakışı

阿里巴巴 Qwen1.5 72B 开源模型, 32K 上下文, 中文理解与生成能力突出, 适合企业部署。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-72b | 2024-02-25 | 32K | text | text | Qwen License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.3 | % | 5-shot |
| HumanEval | 65.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 37.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.5 | % | 3-shot CoT |
| GPQA | 39.8 | % | 0-shot |
| IFEval | 76.4 | % | prompt_strict |
| ARC | 92.6 | % | challenge |
| MUSR | 50.8 | % | 0-shot |
| WinoGrande | 83.1 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 81.3, strong knowledge reasoning.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Qwen1.5 72B Dokümantasyon](https://qwenlm.github.io/)
- Yayın Tarihi: 2024-02-25
- Satıcı: Alibaba
