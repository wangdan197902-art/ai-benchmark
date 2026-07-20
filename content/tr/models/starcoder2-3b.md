---
title: "StarCoder2 3B: Complete Benchmark Performance Guide"
description: "In-depth analysis of StarCoder2 3B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-3b"
vendor: "other"
version: "starcoder2-3b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 3B

## Model Genel Bakışı

BigCode StarCoder2 3B 轻量代码模型, 16K 上下文, 3B 参数, 适合边缘设备代码补全任务。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-3b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.6 | % | 5-shot |
| HumanEval | 82.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.2 | % | 0-shot CoT |
| MATH | 37.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.1 | % | 3-shot CoT |
| GPQA | 36.2 | % | 0-shot |
| IFEval | 55.2 | % | prompt_strict |
| ARC | 87.5 | % | challenge |
| MUSR | 38.4 | % | 0-shot |
| WinoGrande | 76.9 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- HumanEval 82.1, excellent code generation.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [StarCoder2 3B Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2024-02-28
- Satıcı: Other
