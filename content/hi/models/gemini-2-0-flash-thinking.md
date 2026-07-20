---
title: "Gemini 2.0 Flash Thinking: Complete Benchmark Performance Guide"
description: "In-depth analysis of Gemini 2.0 Flash Thinking performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-12-19
lastmod: 2024-12-19
draft: false
weight: 10
model_id: "gemini-2-0-flash-thinking"
vendor: "google"
version: "2.0-flash-thinking"
tags: ["flagship", "reasoning", "multimodal"]
---

# Gemini 2.0 Flash Thinking

## मॉडल अवलोकन

Google Gemini 2.0 Flash Thinking 实验版, 1M 上下文, 链式思维推理, 在数学与编码上接近 o1。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 2.0-flash-thinking | 2024-12-19 | 1048K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.5 | % | 5-shot |
| HumanEval | 87.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.3 | % | 0-shot CoT |
| MATH | 56.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 87.9 | % | 3-shot CoT |
| GPQA | 61.0 | % | 0-shot |
| IFEval | 82.8 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 70.8 | % | 0-shot |
| WinoGrande | 88.1 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 86.5, strong knowledge reasoning.
- HumanEval 87.2, excellent code generation.
- GSM8K 91.3, robust math reasoning.
- 支持文本、图像、音频多模态输入。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## संदर्भ

- [Gemini 2.0 Flash Thinking दस्तावेज़ीकरण](https://ai.google.dev/gemini-api/docs)
- रिलीज़ तिथि: 2024-12-19
- विक्रेता: Google
