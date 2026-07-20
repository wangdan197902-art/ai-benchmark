---
title: "Text Bison: Complete Benchmark Performance Guide"
description: "In-depth analysis of Text Bison performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-05-10
lastmod: 2023-05-10
draft: false
weight: 10
model_id: "text-bison"
vendor: "google"
version: "text-bison"
tags: ["legacy"]
---

# Text Bison

## मॉडल अवलोकन

Google Vertex AI Text Bison 文本生成模型, 基于 PaLM 2, 8K 上下文, 适合指令跟随与生成任务。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | text-bison | 2023-05-10 | 8K | text | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.9 | % | 5-shot |
| HumanEval | 45.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 42.8 | % | 0-shot CoT |
| MATH | 12.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 48.2 | % | 3-shot CoT |
| GPQA | 27.7 | % | 0-shot |
| IFEval | 59.5 | % | prompt_strict |
| ARC | 86.7 | % | challenge |
| MUSR | 40.8 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 53.9，知识推理偏弱。
- HumanEval 45.1，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Text Bison दस्तावेज़ीकरण](https://ai.google.dev/gemini-api/docs)
- रिलीज़ तिथि: 2023-05-10
- विक्रेता: Google
