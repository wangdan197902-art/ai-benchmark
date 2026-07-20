---
title: "Grok-2 Vision: Complete Benchmark Performance Guide"
description: "In-depth analysis of Grok-2 Vision performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2-vision"
vendor: "xai"
version: "2-vision"
tags: ["multimodal"]
---

# Grok-2 Vision

## मॉडल अवलोकन

xAI Grok-2 Vision 多模态模型, 32K 上下文, 支持图像理解, 适合视觉问答与多模态推理。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2-vision | 2024-08-13 | 32K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 84.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.4 | % | 0-shot CoT |
| MATH | 41.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 43.8 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 87.5 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 83.4, strong knowledge reasoning.
- HumanEval 84.2, excellent code generation.
- 支持文本、图像、音频多模态输入。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- 视觉与图像理解

## संदर्भ

- [Grok-2 Vision दस्तावेज़ीकरण](https://docs.x.ai/)
- रिलीज़ तिथि: 2024-08-13
- विक्रेता: Xai
