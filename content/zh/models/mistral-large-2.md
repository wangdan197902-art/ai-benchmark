---
title: "Mistral Large 2：完整基准性能指南"
description: "深入分析 Mistral Large 2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与欧盟数据驻留考量。"
date: 2024-07-24
lastmod: 2024-08-15
draft: false
weight: 80
model_id: "mistral-large-2"
vendor: "mistral"
version: "large-2"
tags: ["旗舰", "代码", "欧盟数据驻留"]
---

# Mistral Large 2

## 模型概述

Mistral Large 2 是 Mistral AI 于 2024 年 7 月 24 日发布的旗舰模型。拥有 123B 参数与 128K 上下文窗口，定位与 GPT-4o、Claude 3.5 Sonnet 在代码、数学与多语言推理上同台竞争。Mistral Large 2 的最大亮点是其欧洲主权属性：由总部位于巴黎的 Mistral AI 研发，支持欧盟数据驻留，符合 GDPR 与 ISO 27001，是欧洲企业及对数据主权要求严苛的公共部门的首选。模型原生支持数十种语言，HumanEval pass@1 达 92.0，跻身顶级代码模型之列。Mistral Large 2 通过 Mistral API、La Plateforme、Azure AI 与 Google Cloud Vertex AI 提供。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Mistral AI |
| 版本 | large-2 |
| 发布日期 | 2024-07-24 |
| 上下文窗口 | 128,000 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | Mistral Research License |
| 文档地址 | https://docs.mistral.ai/ |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 84.0 | % | 5-shot |
| HumanEval | 92.0 | pass@1 | — |
| GSM8K | 93.0 | % | 0-shot CoT |
| MATH | 71.0 | % | 0-shot CoT |
| BBH | 81.0 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $2.00 |
| 输出 | $6.00 |
| 缓存读取 | $0.00 |
| 缓存写入 | $0.00 |

定价来源：https://mistral.ai/technology/ （截至 2024-08-01）。

## 优势

- 顶级代码能力（HumanEval 92.0），与 Claude 3.5 Sonnet 并列。
- 欧盟数据驻留，符合 GDPR 与 ISO 27001。
- 欧洲语言多语言覆盖出色。
- 价格竞争力强，输入 token 比 GPT-4o 便宜 20%。

## 劣势

- 仅文本模型，不支持原生多模态。
- Mistral Research License 对非 Mistral 客户的商用有所限制。
- MMLU 得分（84.0）落后于 GPT-4o（88.7）等头部旗舰。

## 适用场景

- 需 GDPR 合规数据驻留的欧洲企业部署。
- 代码生成与重构工作流。
- 跨欧盟市场的多语言客服。
- 需 ISO 27001 认证的公共部门与监管行业。

## 参考文献

- [Mistral Large 2 发布公告](https://mistral.ai/news/mistral-large-2407/)
- [Mistral AI 文档](https://docs.mistral.ai/)
- [Mistral 技术页](https://mistral.ai/technology/)
