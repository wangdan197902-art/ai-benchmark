---
title: "GLM-4 Air: Complete Benchmark Performance Guide"
description: "In-depth analysis of GLM-4 Air performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-air"
vendor: "other"
version: "glm-4-air"
tags: ["chinese", "realtime"]
---

# GLM-4 Air

## मॉडल अवलोकन

清华智谱 GLM-4 Air 经济型模型, 131K 上下文, 速度快成本低, 适合大规模部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-air | 2024-08-12 | 131K | text | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.9 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.3 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.0 | % | 3-shot CoT |
| GPQA | 31.3 | % | 0-shot |
| IFEval | 75.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 46.7 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [GLM-4 Air दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-08-12
- विक्रेता: Other
