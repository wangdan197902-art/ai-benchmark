---
title: "Gemini 1.5 Flash-8B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 1.5 Flash-8B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-10-03
lastmod: 2024-10-03
draft: false
weight: 10
model_id: "gemini-1-5-flash-8b"
vendor: "google"
version: "1.5-flash-8b"
tags: ["multimodal", "realtime"]
---

# Gemini 1.5 Flash-8B

## मॉडल अवलोकन

Google Gemini 1.5 Flash-8B 8B 参数经济型, 1M 上下文, 更低延迟, 适合高频实时多模态任务。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-8b | 2024-10-03 | 1000K | text, image, audio, video | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 35.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.8 | % | 3-shot CoT |
| GPQA | 35.0 | % | 0-shot |
| IFEval | 68.1 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 45.6 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 支持文本、图像、音频多模态输入。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- 视觉与图像理解

## संदर्भ

- [Gemini 1.5 Flash-8B दस्तावेज़ीकरण](https://ai.google.dev/gemini-api/docs)
- रिलीज़ तिथि: 2024-10-03
- विक्रेता: Google
