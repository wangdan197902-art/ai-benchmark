---
title: "Phi-1: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-1 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-09-14
lastmod: 2023-09-14
draft: false
weight: 10
model_id: "phi-1"
vendor: "other"
version: "phi-1"
tags: ["open-weights", "coding", "self-hostable", "legacy"]
---

# Phi-1

## मॉडल अवलोकन

Microsoft Phi-1 1.3B 代码模型, 2K 上下文, 专为代码生成训练, 在 1.3B 规模上 HumanEval 表现突出。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-1 | 2023-09-14 | 2K | text | text | MIT |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.1 | % | 5-shot |
| HumanEval | 88.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.6 | % | 0-shot CoT |
| MATH | 25.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.9 | % | 3-shot CoT |
| GPQA | 22.1 | % | 0-shot |
| IFEval | 53.8 | % | prompt_strict |
| ARC | 88.4 | % | challenge |
| MUSR | 49.0 | % | 0-shot |
| WinoGrande | 74.5 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- HumanEval 88.1, excellent code generation.

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## उपयोग के मामले

- 代码生成与调试

## संदर्भ

- [Phi-1 दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-09-14
- विक्रेता: Other
