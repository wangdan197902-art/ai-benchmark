---
title: "DeepSeek Coder V2: Complete Benchmark Performance Guide"
description: "In-depth analysis of DeepSeek Coder V2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-21
lastmod: 2024-06-21
draft: false
weight: 10
model_id: "deepseek-coder-v2"
vendor: "deepseek"
version: "coder-v2"
tags: ["open-weights", "coding", "moe"]
---

# DeepSeek Coder V2

## Model Genel Bakışı

DeepSeek Coder V2 代码专用 MoE 模型, 128K 上下文, 支持 338 种编程语言, 代码生成能力突出。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-v2 | 2024-06-21 | 128K | text | text | DeepSeek License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.3 | % | 5-shot |
| HumanEval | 88.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.9 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 25.4 | % | 0-shot |
| IFEval | 56.7 | % | prompt_strict |
| ARC | 88.5 | % | challenge |
| MUSR | 40.3 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- HumanEval 88.9, excellent code generation.
- 采用 MoE 混合专家架构。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试

## Referanslar

- [DeepSeek Coder V2 Dokümantasyon](https://api-docs.deepseek.com/)
- Yayın Tarihi: 2024-06-21
- Satıcı: Deepseek
