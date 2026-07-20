---
title: "Gemini 1.0 Ultra: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.0 Ultra performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-06
lastmod: 2023-12-06
draft: false
weight: 10
model_id: "gemini-1-0-ultra"
vendor: "google"
version: "1.0-ultra"
tags: ["flagship", "multimodal", "legacy"]
---

# Gemini 1.0 Ultra

## मॉडल अवलोकन

Google Gemini 1.0 Ultra 旗舰模型, 32K 上下文, 在多项基准上接近 GPT-4, 多模态推理能力突出。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-ultra | 2023-12-06 | 32K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.3 | % | 5-shot |
| HumanEval | 81.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.9 | % | 0-shot CoT |
| MATH | 57.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.8 | % | 3-shot CoT |
| GPQA | 46.9 | % | 0-shot |
| IFEval | 81.6 | % | prompt_strict |
| ARC | 95.7 | % | challenge |
| MUSR | 64.3 | % | 0-shot |
| WinoGrande | 80.4 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 80.3, strong knowledge reasoning.
- HumanEval 81.7, excellent code generation.
- GSM8K 85.9, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## संदर्भ

- [Gemini 1.0 Ultra दस्तावेज़ीकरण](https://ai.google.dev/gemini-api/docs)
- रिलीज़ तिथि: 2023-12-06
- विक्रेता: Google
