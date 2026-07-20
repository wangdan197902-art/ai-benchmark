---
title: "Mixtral 8x22B：完整基准性能指南"
description: "深入分析 Mistral Mixtral 8x22B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与自托管考量。"
date: 2024-04-10
lastmod: 2024-08-15
draft: false
weight: 50
model_id: "mixtral-8x22b"
vendor: "mistral"
version: "8x22b"
tags: ["开源权重", "MoE", "可自托管"]
---

# Mixtral 8x22B

## 模型概述

Mixtral 8x22B 是 Mistral AI 于 2024 年 4 月 10 日发布的开源权重稀疏混合专家（MoE）模型。架构由 8 个 22B 专家网络组成，总参数 141B、每 token 仅激活约 39B，从而以约三分之一的推理成本达到与 70B 级稠密模型相当的性能。模型支持 64K 上下文窗口，并在英语、法语、意大利语、德语、西班牙语五种语言上具备较强多语言能力。Mixtral 8x22B 以 Apache 2.0 协议发布，是少数可在无任何限制下商用的前沿级模型，允许微调、再分发与集成至专有产品。该模型在 Together AI、Fireworks AI 等推理服务商上广泛部署，亦可自托管于消费级可达的 GPU 集群。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Mistral AI |
| 版本 | 8x22b |
| 发布日期 | 2024-04-10 |
| 上下文窗口 | 64,000 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | Apache 2.0 |
| 文档地址 | https://docs.mistral.ai/ |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 77.8 | % | 5-shot |
| HumanEval | 45.2 | pass@1 | — |
| GSM8K | 78.6 | % | 0-shot CoT |
| MATH | 46.0 | % | 0-shot CoT |
| BBH | 74.5 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入（Mistral 托管） | $1.20 |
| 输出（Mistral 托管） | $1.20 |
| 缓存读取 | $0.00 |
| 缓存写入 | $0.00 |

定价来源：https://mistral.ai/technology/ （截至 2024-08-01）。Apache 2.0 许可证允许无限制自托管。

## 优势

- Apache 2.0 许可证，可无限制商用，包括再分发。
- MoE 架构在推理时性能/算力比突出。
- 英语、法语、德语、意大利语、西班牙语多语言能力强。
- 推理成本低于同等规模的稠密模型。

## 劣势

- 代码能力（HumanEval 45.2）显著落后于旗舰模型。
- 64K 上下文窗口小于较新的开源权重竞品。
- MoE 推理需谨慎处理路由与内存管理，否则吞吐受限。

## 适用场景

- 欧洲市场的成本敏感型多语言文本生成。
- 需宽松许可证的本地客服或 RAG 管道。
- 研究与教育等需要 Apache 2.0 兼容的场景。
- 作为微调领域专用模型的基础。

## 参考文献

- [Mixtral 8x22B 发布公告 — Mistral AI](https://mistral.ai/news/mixtral-8x22b/)
- [Mistral AI 文档](https://docs.mistral.ai/)
- [Mistral 技术页](https://mistral.ai/technology/)
