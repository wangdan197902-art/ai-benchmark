---
title: "Phi-2: Complete Benchmark Performance Guide"
description: "In-depth analysis of Phi-2 performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "phi-2"
vendor: "other"
version: "phi-2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-2

## मॉडल अवलोकन

Microsoft Phi-2 2.7B 模型, 2K 上下文, 在 2.7B 规模上推理能力突出, 适合研究/教育用途。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-2 | 2023-12-11 | 2K | text | text | MIT |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.5 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.8 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.8 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 48.8 | % | prompt_strict |
| ARC | 75.1 | % | challenge |
| MUSR | 23.7 | % | 0-shot |
| WinoGrande | 72.8 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- 可靠的通用模型。

## कमजोरियां

- MMLU 仅 57.5，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## उपयोग के मामले

- 通用对话与问答

## संदर्भ

- [Phi-2 दस्तावेज़ीकरण](https://huggingface.co/models)
- रिलीज़ तिथि: 2023-12-11
- विक्रेता: Other
