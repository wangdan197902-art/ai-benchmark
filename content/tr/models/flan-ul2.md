---
title: "Flan-UL2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Flan-UL2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-03-03
lastmod: 2023-03-03
draft: false
weight: 10
model_id: "flan-ul2"
vendor: "other"
version: "flan-ul2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-UL2

## Model Genel Bakışı

Google Flan-UL2 20B 指令微调模型, 4K 上下文, 基于 UL2 框架, 适合多任务与零样本推理。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-ul2 | 2023-03-03 | 4K | text | text | Apache 2.0 |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.7 | % | 5-shot |
| HumanEval | 46.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.6 | % | 0-shot CoT |
| MATH | 22.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 88.8 | % | challenge |
| MUSR | 37.2 | % | 0-shot |
| WinoGrande | 76.2 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- 可靠的通用模型。

## Zayıf Yönler

- MMLU 仅 58.7，知识推理偏弱。
- HumanEval 46.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## Kullanım Senaryoları

- 通用对话与问答

## Referanslar

- [Flan-UL2 Dokümantasyon](https://huggingface.co/models)
- Yayın Tarihi: 2023-03-03
- Satıcı: Other
