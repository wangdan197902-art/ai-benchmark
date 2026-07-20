---
title: "Zephyr ORPO 141B Alpha: Complete Benchmark Performance Guide"
description: "In-depth analysis of Zephyr ORPO 141B Alpha performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-03-22
lastmod: 2024-03-22
draft: false
weight: 10
model_id: "zephyr-orpo-141b-alpha"
vendor: "other"
version: "zephyr-orpo-141b-alpha"
tags: ["open-weights", "moe", "self-hostable"]
---

# Zephyr ORPO 141B Alpha

## मॉडल अवलोकन

HuggingFaceH4 Zephyr ORPO 141B Alpha, 4K 上下文, 基于 Mixtral 8x22B ORPO 微调, 性能接近 GPT-4。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | zephyr-orpo-141b-alpha | 2024-03-22 | 4K | text | text | Apache 2.0 |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.5 | % | 5-shot |
| HumanEval | 74.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.6 | % | 0-shot CoT |
| MATH | 36.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.3 | % | 3-shot CoT |
| GPQA | 36.8 | % | 0-shot |
| IFEval | 69.7 | % | prompt_strict |
| ARC | 91.4 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 采用 MoE 混合专家架构。

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## उपयोग के मामले

- 代码生成与调试

## संदर्भ

- [Zephyr ORPO 141B Alpha दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-03-22
- विक्रेता: Other
