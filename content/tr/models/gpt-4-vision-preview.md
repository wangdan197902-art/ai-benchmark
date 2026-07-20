---
title: "GPT-4 Vision Preview: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4 Vision Preview performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-25
lastmod: 2023-09-25
draft: false
weight: 10
model_id: "gpt-4-vision-preview"
vendor: "openai"
version: "4-vision-preview"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision Preview

## Model Genel Bakışı

OpenAI GPT-4 Vision 预览版, 支持图像输入理解, 128K 上下文, 多模态能力首次集成。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision-preview | 2023-09-25 | 128K | text, image | text | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.0 | % | 5-shot |
| HumanEval | 70.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 49.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 72.7 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.5 | % | 0-shot |
| WinoGrande | 80.6 | % | 0-shot |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 85.0, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Referanslar

- [GPT-4 Vision Preview Dokümantasyon](https://platform.openai.com/docs/models)
- Yayın Tarihi: 2023-09-25
- Satıcı: Openai
