---
title: "Grok Beta: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok Beta performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-beta"
vendor: "xai"
version: "beta"
tags: ["legacy", "realtime"]
---

# Grok Beta

## Model Genel Bakışı

xAI Grok Beta 早期预览版, 8K 上下文, 集成 X 平台实时数据, 幽默风格对话能力突出。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | beta | 2023-11-04 | 8K | text | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 31.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.7 | % | 0-shot CoT |
| MATH | 19.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 20.6 | % | 0-shot |
| IFEval | 56.2 | % | prompt_strict |
| ARC | 81.7 | % | challenge |
| MUSR | 43.7 | % | 0-shot |
| WinoGrande | 69.2 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 31.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Grok Beta Dokümantasyon](https://docs.x.ai/)
- Yayın Tarihi: 2023-11-04
- Satıcı: Xai
