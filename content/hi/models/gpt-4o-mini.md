---
title: "GPT-4o mini: Complete Benchmark Performance Guide"
description: "In-depth analysis of GPT-4o mini performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-18
lastmod: 2024-07-18
draft: false
weight: 10
model_id: "gpt-4o-mini"
vendor: "openai"
version: "4o-mini"
tags: ["multimodal", "realtime"]
---

# GPT-4o mini

## मॉडल अवलोकन

OpenAI 经济型多模态模型, 128K 上下文, 支持文本与图像输入, 平衡成本与性能, 适合大规模部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4o-mini | 2024-07-18 | 128K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.7 | % | 5-shot |
| HumanEval | 78.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 75.1 | % | 0-shot CoT |
| MATH | 51.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 42.6 | % | 0-shot |
| IFEval | 67.9 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 53.1 | % | 0-shot |
| WinoGrande | 79.6 | % | 0-shot |

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

- [GPT-4o mini दस्तावेज़ीकरण](https://platform.openai.com/docs/models)
- रिलीज़ तिथि: 2024-07-18
- विक्रेता: Openai
