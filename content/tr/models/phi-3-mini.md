---
title: "Phi-3 Mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-04-22
lastmod: 2024-04-22
draft: false
weight: 10
model_id: "phi-3-mini"
vendor: "other"
version: "phi-3-mini"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Mini

## Model Genel Bakışı

Microsoft Phi-3 Mini 3.8B 轻量模型, 4K 上下文 (可扩展 128K), 训练数据高质量, 性能超越 Llama 2 7B。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-mini | 2024-04-22 | 4K | text | text | MIT |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 43.6 | % | 5-shot |
| HumanEval | 26.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.9 | % | 0-shot CoT |
| MATH | 17.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.9 | % | 3-shot CoT |
| GPQA | 20.7 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 84.4 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 67.1 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- MMLU 仅 43.6，知识推理偏弱。
- HumanEval 26.9，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Phi-3 Mini Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2024-04-22
- Satıcı: Other
