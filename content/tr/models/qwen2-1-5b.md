---
title: "Qwen2 1.5B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2 1.5B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-06-07
lastmod: 2024-06-07
draft: false
weight: 10
model_id: "qwen2-1-5b"
vendor: "alibaba"
version: "2-1-5b"
tags: ["open-weights", "chinese", "self-hostable"]
---

# Qwen2 1.5B

## Model Genel Bakışı

阿里巴巴 Qwen2 1.5B 轻量开源模型, 32K 上下文, 1.5B 参数, 适合边缘设备与移动部署。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2-1-5b | 2024-06-07 | 32K | text | text | Qwen License |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 40.5 | % | 5-shot |
| HumanEval | 47.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.2 | % | 0-shot CoT |
| MATH | 25.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 51.5 | % | 3-shot CoT |
| GPQA | 22.1 | % | 0-shot |
| IFEval | 57.4 | % | prompt_strict |
| ARC | 85.4 | % | challenge |
| MUSR | 27.8 | % | 0-shot |
| WinoGrande | 62.9 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- MMLU 仅 40.5，知识推理偏弱。
- HumanEval 47.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Qwen2 1.5B Dokümantasyon](https://qwenlm.github.io/)
- Yayın Tarihi: 2024-06-07
- Satıcı: Alibaba
