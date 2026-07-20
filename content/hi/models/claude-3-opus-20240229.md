---
title: "Claude 3 Opus (2024-02-29): Complete Benchmark Performance Guide"
description: "In-depth analysis of Claude 3 Opus (2024-02-29) performance on MMLU, HumanEval, GSM8K, MATH, BBH benchmarks, including pricing and use cases."
date: 2024-02-29
lastmod: 2024-02-29
draft: false
weight: 10
model_id: "claude-3-opus-20240229"
vendor: "anthropic"
version: "3-opus-20240229"
tags: ["flagship", "multimodal", "long-context"]
---

# Claude 3 Opus (2024-02-29)

## मॉडल अवलोकन

Anthropic Claude 3 Opus 2024-02-29 快照版本, 200K 上下文, 旗舰级推理能力。

## मुख्य विशिष्टताएं

| विक्रेता | संस्करण | रिलीज़ तिथि | संदर्भ विंडो | इनपुट मोडलिटी | आउटपुट मोडलिटी | लाइसेंस |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 3-opus-20240229 | 2024-02-29 | 200K | text, image | text | Proprietary |

## बेंचमार्क प्रदर्शन

| बेंचमार्क | स्कोर | इकाई | टिप्पणियाँ |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.7 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.3 | % | 0-shot CoT |
| MATH | 58.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.5 | % | 3-shot CoT |
| GPQA | 38.6 | % | 0-shot |
| IFEval | 75.5 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 57.3 | % | 0-shot |
| WinoGrande | 87.8 | % | 0-shot |

## मूल्य निर्धारण

| इनपुट | आउटपुट | कैश पढ़ें | कैश लिखें |
|------|--------|-----------|-----------|
| — | — | — | — |

*प्रति मिलियन टोकन*

## ताकत

- MMLU score 85.7, strong knowledge reasoning.
- 支持文本、图像、音频多模态输入。
- 上下文窗口 200K，支持长文本。

## कमजोरियां

- 闭源专有模型，不支持自托管。

## उपयोग के मामले

- 代码生成与调试
- 长文档摘要
- 视觉与图像理解
- Agent 工作流与工具调用

## संदर्भ

- [Claude 3 Opus (2024-02-29) दस्तावेज़ीकरण](https://docs.anthropic.com/claude/docs)
- रिलीज़ तिथि: 2024-02-29
- विक्रेता: Anthropic
