---
title: "GPT-4o：完整基准性能指南"
description: "深入分析 GPT-4o 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-13
lastmod: 2024-08-15
draft: false
weight: 10
model_id: "gpt-4o"
vendor: "openai"
version: "4o"
tags: ["旗舰", "多模态", "openai"]
---

# GPT-4o

## 模型概述

GPT-4o 是 OpenAI 于 2024 年 5 月 13 日发布的旗舰多模态模型。"o" 代表 omni（全能），反映出该模型在单一神经网络中原生支持文本、图像、音频三种模态的输入与输出。GPT-4o 拥有 128K 上下文窗口，并针对低延迟进行了优化，能够支撑实时语音对话、视觉任务以及高吞吐文本生成。在学术基准上，GPT-4o 与 GPT-4 Turbo 持平或更优，同时价格降低 50%、速度提升 2 倍。该模型驱动 ChatGPT 的语音模式、视觉功能以及 OpenAI API 的旗舰层级，是当前需要多模态理解的生产级通用工作流的默认选择。GPT-4o 也是 OpenAI 首个使用跨模态统一分词器训练的模型，显著提升了非英语语言的质量。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | OpenAI |
| 版本 | 4o |
| 发布日期 | 2024-05-13 |
| 上下文窗口 | 128,000 tokens |
| 输入模态 | 文本、图像、音频 |
| 输出模态 | 文本、音频 |
| 许可证 | 专有 |
| 文档地址 | https://platform.openai.com/docs/models/gpt-4o |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 88.7 | % | 5-shot |
| HumanEval | 90.2 | pass@1 | — |
| GSM8K | 95.8 | % | 0-shot CoT |
| MATH | 76.6 | % | 0-shot CoT |
| BBH | 83.1 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $2.50 |
| 输出 | $10.00 |
| 缓存读取 | $1.25 |
| 缓存写入 | $2.50 |

定价来源：https://openai.com/api/pricing/ （截至 2024-08-01）。

## 优势

- 原生支持文本、图像、音频三种模态，单模型完成多模态理解。
- 在推理与代码生成上表现强劲，GSM8K 得分在闭源旗舰中领先。
- 延迟低于 GPT-4 Turbo，可支撑实时语音应用。
- 得益于统一分词器，多语言能力稳健。

## 劣势

- 闭源专有模型，不支持自托管。
- 128K 上下文窗口小于 Gemini 1.5 Pro（2M）和 Claude 3.5 Sonnet（200K）。
- 价格高于 DeepSeek V3、Qwen2.5 72B 等开源权重竞品。

## 适用场景

- 实时语音助手与对话代理。
- 需要同时理解图像与文本的多模态应用。
- 需要低延迟响应的生产级聊天机器人。
- 融合视觉、音频与工具调用的 Agent 工作流。

## 参考文献

- [Hello GPT-4o — OpenAI](https://openai.com/index/hello-gpt-4o/)
- [OpenAI API 定价](https://openai.com/api/pricing/)
- [GPT-4o 文档](https://platform.openai.com/docs/models/gpt-4o)
