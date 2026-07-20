---
title: "Mistral Large 2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Mistral Large 2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
model_id: "mistral-large-2"
vendor: "mistral"
version: "large-2"
tags: ["flagship", "coding", "eu-residency"]
---

# Mistral Large 2

## मॉडल अवलोकन

Mistral Large 2 是 Mistral AI 旗舰模型，123B 参数，128K 上下文窗口，在代码生成、数学推理与多语言任务上表现强劲，支持欧盟数据驻留与 GDPR/ISO 27001 合规。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large-2 | 2024-07-24 | 128K | text | text | Mistral Research License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.0 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 93.0 | % | 0-shot CoT |
| MATH | 71.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 81.0 | % | 3-shot CoT |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 84.0, strong knowledge reasoning.
- HumanEval 92.0, excellent code generation.
- GSM8K 93.0, robust math reasoning.

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- Agent 工作流与工具调用

## संदर्भ

- [Mistral Large 2 दस्तावेज़ीकरण](https://docs.mistral.ai/)
- रिलीज़ तिथि: 2024-07-24
- विक्रेता: Mistral
