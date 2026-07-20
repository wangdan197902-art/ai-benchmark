---
title: "Phi-3 Small: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-3 Small performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-05-21
lastmod: 2024-05-21
draft: false
weight: 10
model_id: "phi-3-small"
vendor: "other"
version: "phi-3-small"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Small

## मॉडल अवलोकन

Microsoft Phi-3 Small 7.4B 模型, 8K 上下文, 在 7B 规模上推理能力突出, 适合移动设备部署。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-small | 2024-05-21 | 8K | text | text | MIT |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 71.8 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.7 | % | 0-shot CoT |
| MATH | 43.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 30.9 | % | 0-shot |
| IFEval | 61.0 | % | prompt_strict |
| ARC | 89.6 | % | challenge |
| MUSR | 36.5 | % | 0-shot |
| WinoGrande | 74.9 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Phi-3 Small दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2024-05-21
- विक्रेता: Other
