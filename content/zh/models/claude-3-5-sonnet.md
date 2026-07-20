---
title: "Claude 3.5 Sonnet：完整基准性能指南"
description: "深入分析 Claude 3.5 Sonnet 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-06-20
lastmod: 2024-08-15
draft: false
weight: 20
model_id: "claude-3-5-sonnet"
vendor: "anthropic"
version: "3.5-sonnet"
tags: ["旗舰", "代码", "长上下文"]
---

# Claude 3.5 Sonnet

## 模型概述

Claude 3.5 Sonnet 是 Anthropic 于 2024 年 6 月 20 日发布的 2024 年中旗舰模型。它在编程、视觉推理与长文档理解方面显著提升，同时保留 200K 上下文窗口。尽管在 Claude 3.5 家族中定位为"中端"，Sonnet 在几乎全部学术基准上超越了上一代 Claude 3 Opus，并以两倍速度运行。Anthropic 强调 Constitutional AI 对齐、行为可预测性，以及对复杂工具调用与 Agent 工作流的强支持，使其在企业级生产部署中备受青睐。Claude 3.5 Sonnet 也是首个随 Claude.ai 网页端推出 Artifacts 功能的模型，可在对话中交互式生成代码与内容。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Anthropic |
| 版本 | 3.5-sonnet |
| 发布日期 | 2024-06-20 |
| 上下文窗口 | 200,000 tokens |
| 输入模态 | 文本、图像 |
| 输出模态 | 文本 |
| 许可证 | 专有 |
| 文档地址 | https://docs.anthropic.com/claude/docs |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 88.7 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K | 96.4 | % | 0-shot CoT |
| MATH | 71.1 | % | 0-shot CoT |
| BBH | 84.5 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $3.00 |
| 输出 | $15.00 |
| 缓存读取 | $0.30 |
| 缓存写入 | $3.75 |

定价来源：https://www.anthropic.com/pricing （截至 2024-08-01）。

## 优势

- HumanEval 行业领先的 92.0 pass@1，是代码生成的首选模型。
- 200K 长上下文窗口，适合长文档分析与代码库推理。
- 支持图像输入，可处理图表、截图与文档理解。
- 工具调用与 Agent 工作流稳定性强。

## 劣势

- 不支持音频模态（仅文本与图像输入）。
- 输入 token 价格比 GPT-4o 高 20%-50%。
- 不支持自托管，仅通过 Anthropic API 或云合作伙伴提供。

## 适用场景

- 生产级代码生成与重构。
- 长文档摘要、法律/金融分析。
- 跨文本与图像的多模态推理。
- 涉及工具调用与结构化输出的 Agent 自动化。

## 参考文献

- [Claude 3.5 Sonnet 发布公告 — Anthropic](https://www.anthropic.com/news/claude-3-5-sonnet)
- [Anthropic 定价](https://www.anthropic.com/pricing)
- [Claude 文档](https://docs.anthropic.com/claude/docs)
