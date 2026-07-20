---
title: "Mixtral 8x22B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mixtral 8x22B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-10
lastmod: 2024-04-10
draft: false
weight: 10
model_id: "mixtral-8x22b"
vendor: "mistral"
version: "8x22b"
tags: ["open-weights", "moe", "self-hostable"]
---

# Mixtral 8x22B

## Model Genel Bakışı

Mistral Mixtral 8x22B 是稀疏混合专家（MoE）开源模型，总参数 141B、活跃参数 39B，64K 上下文窗口，在多语言与代码任务上表现稳健，Apache 2.0 许可证可商用。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 8x22b | 2024-04-10 | 64K | text | text | Apache 2.0 |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 77.8 | % | 5-shot |
| HumanEval | 45.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.6 | % | 0-shot CoT |
| MATH | 46.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.5 | % | 3-shot CoT |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 采用 MoE 混合专家架构。

## Zayıf Yönler

- HumanEval 45.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Mixtral 8x22B Dokümantasyon](https://docs.mistral.ai/)
- Yayın Tarihi: 2024-04-10
- Satıcı: Mistral
