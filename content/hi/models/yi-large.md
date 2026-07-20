---
title: "Yi Large: Complete Benchmark Performance Guide"
description: "In-depth analysis of Yi Large performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-13
lastmod: 2024-05-13
draft: false
weight: 10
model_id: "yi-large"
vendor: "other"
version: "yi-large"
tags: ["flagship", "chinese"]
---

# Yi Large

## मॉडल अवलोकन

01.AI Yi Large 旗舰闭源模型, 32K 上下文, 中英文能力突出, 在 LMSYS 排行榜上接近 GPT-4。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-large | 2024-05-13 | 32K | text | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.8 | % | 5-shot |
| HumanEval | 72.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.3 | % | 0-shot CoT |
| MATH | 55.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 77.1 | % | 3-shot CoT |
| GPQA | 35.2 | % | 0-shot |
| IFEval | 73.4 | % | prompt_strict |
| ARC | 94.8 | % | challenge |
| MUSR | 59.4 | % | 0-shot |
| WinoGrande | 84.1 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 82.8, strong knowledge reasoning.

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- Agent 工作流与工具调用

## संदर्भ

- [Yi Large दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-05-13
- विक्रेता: Other
