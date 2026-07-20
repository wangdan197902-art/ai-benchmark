---
title: "Command R+：完整基准性能指南"
description: "深入分析 Cohere Command R+ 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与企业 RAG 考量。"
date: 2024-04-04
lastmod: 2024-08-15
draft: false
weight: 90
model_id: "command-r-plus"
vendor: "cohere"
version: "r-plus"
tags: ["RAG", "企业级", "工具调用"]
---

# Command R+

## 模型概述

Command R+ 是 Cohere 于 2024 年 4 月 4 日发布的企业级旗舰模型。拥有 104B 参数与 128K 上下文窗口，模型专门针对检索增强生成（RAG）、工具调用与结构化输出优化——这些工作流在企业生产部署中占主导地位。Cohere 将 Command R+ 定位为构建生产级 RAG 管道的首选，强调其在引用质量与答案扎实度（groundedness）上业界领先。模型原生支持工具调用、JSON 模式输出以及对检索文档的多步推理。Cohere 同样强调数据隐私：客户提示绝不用于训练，模型可通过 AWS、Azure、Google Cloud、Oracle Cloud 调用，并具备 SOC2、GDPR、ISO 27001 合规认证。Command R+ 研究版以 CC-BY-NC-4.0 协议发布，商用须通过 Cohere API。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Cohere |
| 版本 | r-plus |
| 发布日期 | 2024-04-04 |
| 上下文窗口 | 128,000 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | CC-BY-NC-4.0（研究用）；商用通过 Cohere API |
| 文档地址 | https://docs.cohere.com/docs/command-r-plus |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 75.0 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K | 68.4 | % | 0-shot CoT |
| MATH | 35.6 | % | 0-shot CoT |
| BBH | 66.1 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $2.50 |
| 输出 | $10.00 |
| 缓存读取 | $0.00 |
| 缓存写入 | $0.00 |

定价来源：https://cohere.com/pricing （截至 2024-08-01）。

## 优势

- 业界领先的 RAG 表现，引用扎实度强。
- 原生工具调用与结构化输出，适合 Agent 工作流。
- 企业级合规：SOC2、GDPR、ISO 27001，承诺不用于训练。
- 全部主流云厂商均可调用。

## 劣势

- 通用推理基准（MMLU 75.0）显著落后头部旗舰。
- CC-BY-NC-4.0 非商业许可，生产环境不可自托管。
- 价格与 GPT-4o 持平，但原始基准分数更低。

## 适用场景

- 法律、金融、医疗知识库的生产级 RAG 管道。
- 带引用扎根的客服自动化。
- 涉及工具调用与结构化输出的企业 Agent 工作流。
- 严格数据驻留要求的多语言企业搜索。

## 参考文献

- [Command R+ 发布公告 — Cohere](https://txt.cohere.com/command-r-plus-microsoft-azure)
- [Cohere 定价](https://cohere.com/pricing)
- [Command R+ 文档](https://docs.cohere.com/docs/command-r-plus)
