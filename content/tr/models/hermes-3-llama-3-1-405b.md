---
title: "Hermes 3 Llama 3.1 405B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Hermes 3 Llama 3.1 405B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-405b"
vendor: "other"
version: "hermes-3-llama-3-1-405b"
tags: ["open-weights", "reasoning", "self-hostable"]
---

# Hermes 3 Llama 3.1 405B

## Model Genel Bakışı

NousResearch Hermes 3 Llama 3.1 405B 微调模型, 131K 上下文, 改进中立性与推理, 性能超越基座模型。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-405b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.9 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 88.9 | % | 0-shot CoT |
| MATH | 65.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 40.5 | % | 0-shot |
| IFEval | 78.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 86.5 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 83.9, strong knowledge reasoning.
- HumanEval 89.0, excellent code generation.
- GSM8K 88.9, robust math reasoning.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [Hermes 3 Llama 3.1 405B Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2024-08-12
- Satıcı: Other
