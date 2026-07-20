---
title: "Qwen2.5 72B：完整基准性能指南"
description: "深入分析阿里巴巴 Qwen2.5 72B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-19
lastmod: 2024-09-19
draft: false
weight: 60
model_id: "qwen2-5-72b"
vendor: "alibaba"
version: "2.5-72b"
tags: ["开源权重", "中文", "代码"]
---

# Qwen2.5 72B

## 模型概述

Qwen2.5 72B 是阿里巴巴于 2024 年 9 月 19 日发布的开源权重旗舰模型，是 Qwen2.5 系列的一员。模型在中文理解上处于领先地位，覆盖 29+ 种语言，拥有 131K 上下文窗口。在学术基准上，Qwen2.5 72B 在 MMLU（86.1）上与 Llama 3.1 70B 持平或略胜，并在数学（83.1 vs 71.8）和代码（HumanEval 86.6 pass@1）上显著领先。模型以 Qwen License 发布，对商用几乎无限制（仅有少量使用约束），已成为中文市场部署、中英双语 RAG 系统、以及涉及中文上下文的代码生成管道的首选。模型原生支持结构化输出、工具调用与长文档摘要。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | 阿里巴巴 |
| 版本 | 2.5-72b |
| 发布日期 | 2024-09-19 |
| 上下文窗口 | 131,072 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | Qwen License |
| 文档地址 | https://qwenlm.github.io/ |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 86.1 | % | 5-shot |
| HumanEval | 86.6 | pass@1 | — |
| GSM8K | 88.4 | % | 0-shot CoT |
| MATH | 83.1 | % | 0-shot CoT |
| BBH | 82.4 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入（阿里云） | $0.50 |
| 输出（阿里云） | $0.80 |
| 缓存读取 | $0.00 |
| 缓存写入 | $0.00 |

定价来源：https://help.aliyun.com/zh/model-studio/getting-started/models （截至 2024-09-19）。开源权重亦允许自托管。

## 优势

- 开源权重模型中中文理解能力领先。
- 代码与数学表现强劲，在多项基准上超越 Llama 3.1 70B。
- 131K 上下文窗口可处理长中文文档与代码库。
- API 定价竞争力强，仅 $0.50/$0.80 每百万 token。

## 劣势

- Qwen License 较 Apache 2.0 存在少量商用限制。
- 厂商生态以中国为主，海外社区工具链成熟度较低。
- 72B 文本版本不支持原生多模态（Qwen2.5-VL 为独立模型）。

## 适用场景

- 中国市场的客服与内容生成。
- 中英双语 RAG 系统，需平衡中英文检索。
- 面向中文开发者的代码生成管道。
- 需要强数学与推理且成本敏感的学术研究。

## 参考文献

- [Qwen2.5 博客](https://qwenlm.github.io/blog/qwen2.5/)
- [阿里云百炼平台](https://help.aliyun.com/zh/model-studio/getting-started/models)
- [Qwen 文档](https://qwenlm.github.io/)
