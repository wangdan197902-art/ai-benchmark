---
title: "Gemini 1.5 Pro：完整基准性能指南"
description: "深入分析 Gemini 1.5 Pro 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-15
lastmod: 2024-08-15
draft: false
weight: 30
model_id: "gemini-1-5-pro"
vendor: "google"
version: "1.5-pro"
tags: ["旗舰", "多模态", "长上下文"]
---

# Gemini 1.5 Pro

## 模型概述

Gemini 1.5 Pro 是 Google DeepMind 于 2024 年 2 月 15 日发布的旗舰多模态模型。其最大亮点是行业领先的 200 万 token 上下文窗口，可在单次调用中完成整个代码库推理、多小时视频理解与百万字文档分析。模型原生接受文本、图像、音频、视频四种输入，是唯一将视频作为一等模态处理的旗舰。Gemini 1.5 Pro 基于 MoE 架构，在多数基准上达到接近头部闭源旗舰的水平，价格约为 GPT-4o 的一半。它驱动 Gemini Advanced 消费产品、Google Cloud Vertex AI 以及 Google Workspace AI 功能。其长上下文能力对处理大型法律合同、财务报告或研究语料库的企业尤为关键。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Google DeepMind |
| 版本 | 1.5-pro |
| 发布日期 | 2024-02-15 |
| 上下文窗口 | 2,000,000 tokens |
| 输入模态 | 文本、图像、音频、视频 |
| 输出模态 | 文本 |
| 许可证 | 专有 |
| 文档地址 | https://ai.google.dev/gemini-api/docs |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 85.9 | % | 5-shot |
| HumanEval | 71.9 | pass@1 | — |
| GSM8K | 91.7 | % | 0-shot CoT |
| MATH | 58.5 | % | 0-shot CoT |
| BBH | 84.0 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $1.25 |
| 输出 | $5.00 |
| 缓存读取 | $0.3125 |
| 缓存写入 | $1.25 |

定价来源：https://ai.google.dev/pricing （截至 2024-08-01）。

## 优势

- 行业领先的 2M token 上下文窗口，可处理超长输入。
- 原生视频模态支持，在旗舰模型中独树一帜。
- 定价竞争力强，约为 GPT-4o 的一半。
- 跨文本、图像、音频、视频的多模态理解稳健。

## 劣势

- HumanEval 得分（71.9）在纯代码任务上落后于 GPT-4o 与 Claude 3.5 Sonnet。
- 对输入深处事实的长上下文召回稳定性偶有波动。
- 闭源专有模型，不支持自托管。

## 适用场景

- 整代码库的重构与分析。
- 长视频摘要与内容审核。
- 多文档法律与财务研究。
- 跨媒体归档的多模态检索。

## 参考文献

- [Gemini 1.5 Pro — Google DeepMind](https://deepmind.google/technologies/gemini/)
- [Gemini API 定价](https://ai.google.dev/pricing)
- [Gemini API 文档](https://ai.google.dev/gemini-api/docs)
