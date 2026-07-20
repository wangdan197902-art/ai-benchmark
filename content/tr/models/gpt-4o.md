---
title: "GPT-4o: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4o performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "gpt-4o"
vendor: "openai"
version: "4o"
tags: ["flagship", "multimodal", "reasoning"]
---

# GPT-4o

## Model Genel Bakışı

OpenAI 旗舰多模态模型，支持文本、图像、音频输入与文本、音频输出，128K 上下文窗口，在 MMLU、HumanEval、GSM8K 等基准上表现领先。

## Temel Özellikler

| Satıcı | Sürüm | Yayın Tarihi | Bağlam Penceresi | Giriş Modları | Çıkış Modları | Lisans |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4o | 2024-05-13 | 128K | text, image, audio | text, audio | Proprietary |

## Benchmark Performansı

| Benchmark | Puan | Birim | Notlar |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 88.7 | % | 5-shot |
| HumanEval | 90.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 95.8 | % | 0-shot CoT |
| MATH | 76.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.1 | % | 3-shot CoT |

## Fiyatlandırma

| Giriş | Çıkış | Önbellek Okuma | Önbellek Yazma |
|------|--------|-----------|-----------|
| — | — | — | — |

*milyon token başına*

## Güçlü Yönler

- MMLU score 88.7, strong knowledge reasoning.
- HumanEval 90.2, excellent code generation.
- GSM8K 95.8, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## Zayıf Yönler

- 闭源专有模型，不支持自托管。

## Kullanım Senaryoları

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## Referanslar

- [GPT-4o Dokümantasyon](https://platform.openai.com/docs/models/gpt-4o)
- Yayın Tarihi: 2024-05-13
- Satıcı: Openai
