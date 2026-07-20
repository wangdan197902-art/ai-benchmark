---
title: "Qwen1.5 14B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen1.5 14B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-14b"
vendor: "alibaba"
version: "1.5-14b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 14B

## मॉडल अवलोकन

阿里巴巴 Qwen1.5 14B 中型开源模型, 32K 上下文, 平衡性能与资源, 适合企业级应用。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-14b | 2024-02-25 | 32K | text | text | Qwen License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 65.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 46.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.6 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 79.9 | % | prompt_strict |
| ARC | 92.7 | % | challenge |
| MUSR | 58.7 | % | 0-shot |
| WinoGrande | 78.6 | % | 0-shot |

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

- [Qwen1.5 14B दस्तावेज़ीकरण](https://qwenlm.github.io/)
- रिलीज़ तिथि: 2024-02-25
- विक्रेता: Alibaba
