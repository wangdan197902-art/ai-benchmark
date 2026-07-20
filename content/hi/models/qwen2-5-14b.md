---
title: "Qwen2.5 14B: Complete Benchmark Performance Guide"
description: "In-depth analysis of Qwen2.5 14B performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 10
model_id: "qwen2-5-14b"
vendor: "alibaba"
version: "2.5-14b"
tags: ["open-weights", "chinese"]
---

# Qwen2.5 14B

## मॉडल अवलोकन

阿里巴巴 Qwen2.5 14B 开源中型模型, 131K 上下文, 平衡性能与资源, 适合企业级部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 2.5-14b | 2024-09-19 | 131K | text | text | Qwen License |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.4 | % | 5-shot |
| HumanEval | 72.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 38.8 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.2 | % | 3-shot CoT |
| GPQA | 44.5 | % | 0-shot |
| IFEval | 74.1 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 50.5 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

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

- 代码生成与调试

## संदर्भ

- [Qwen2.5 14B दस्तावेज़ीकरण](https://qwenlm.github.io/)
- रिलीज़ तिथि: 2024-09-19
- विक्रेता: Alibaba
