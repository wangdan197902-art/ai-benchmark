---
title: "o1 Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of o1 Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-12
lastmod: 2024-09-12
draft: false
weight: 10
model_id: "o1-preview"
vendor: "openai"
version: "o1-preview"
tags: ["flagship", "reasoning"]
---

# o1 Preview

## Model Genel Bakışı

OpenAI o1 预览版推理模型, 128K 上下文, 通过链式思维推理在数学/编码/科学任务上达到博士级表现。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | o1-preview | 2024-09-12 | 128K | text | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.3 | % | 5-shot |
| HumanEval | 90.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 92.5 | % | 0-shot CoT |
| MATH | 71.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 84.5 | % | 3-shot CoT |
| GPQA | 57.7 | % | 0-shot |
| IFEval | 84.4 | % | prompt_strict |
| ARC | 96.0 | % | challenge |
| MUSR | 64.1 | % | 0-shot |
| WinoGrande | 85.2 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 85.3, strong knowledge reasoning.
- HumanEval 90.1, excellent code generation.
- GSM8K 92.5, robust math reasoning.

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试
- Agent 工作流与工具调用

## Referanslar

- [o1 Preview Dokümantasyon](https://platform.openai.com/docs/models)
- Yayın Tarihi: 2024-09-12
- Satıcı: Openai
