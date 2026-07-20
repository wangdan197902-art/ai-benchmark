---
title: "Llama 3.1 405B：完整基准性能指南"
description: "深入分析 Meta Llama 3.1 405B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与自托管考量。"
date: 2024-07-23
lastmod: 2024-08-15
draft: false
weight: 40
model_id: "llama-3-1-405b"
vendor: "meta"
version: "3.1-405b"
tags: ["开源权重", "推理", "可自托管"]
---

# Llama 3.1 405B

## 模型概述

Llama 3.1 405B 是 Meta 于 2024 年 7 月 23 日发布的开源权重旗舰模型。拥有 4050 亿参数与 128K 上下文窗口，是迄今公开可用的最大基础模型。Meta 公布的数据显示，Llama 3.1 405B 在 MMLU、HumanEval、MATH 等基准上已逼近 GPT-4o、Claude 3.5 Sonnet 等闭源旗舰，让对模型控制权有强需求（合规、隐私、定制）的组织得以在自己的基础设施上部署接近前沿水平的模型。权重以 Llama 3 Community License 发布，月活低于 7 亿的用户可商用。模型可通过 AWS、Azure、Google Cloud 等主流云厂商调用，也可在 8× H100 GPU 集群上自托管。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | Meta |
| 版本 | 3.1-405b |
| 发布日期 | 2024-07-23 |
| 上下文窗口 | 128,000 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | Llama 3 Community License |
| 文档地址 | https://llama.meta.com/docs/ |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 88.6 | % | 5-shot |
| HumanEval | 89.0 | pass@1 | — |
| GSM8K | 89.2 | % | 0-shot CoT |
| MATH | 73.8 | % | 0-shot CoT |
| BBH | 82.9 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入（Together AI 托管） | $5.00 |
| 输出（Together AI 托管） | $15.00 |
| 缓存读取 | $0.00 |
| 缓存写入 | $0.00 |

定价来源：https://www.together.ai/pricing （截至 2024-08-01）。自托管成本视 GPU 基础设施而定。

## 优势

- 当前最大开源权重模型，性能接近前沿闭源旗舰。
- 模型权重完全可控，适合合规要求严苛的行业（国防、医疗、金融）。
- Llama 3 Community License 允许大多数组织商用。
- 生态成熟，vLLM、TGI、TensorRT-LLM 等推理栈支持完善。

## 劣势

- 自托管需要大量 GPU 资源（建议 8× H100 80GB）。
- 不支持原生多模态（仅文本）。
- 自托管会引入推理、扩展、监控等运维复杂度。

## 适用场景

- 监管行业的本地化部署。
- 自定义微调与领域适配。
- 需要完全数据主权的主权 AI 项目。
- 需要权重级访问的研究工作负载。

## 参考文献

- [Meta Llama 3.1 发布公告](https://ai.meta.com/blog/meta-llama-3-1/)
- [Llama 文档](https://llama.meta.com/docs/)
- [Together AI 定价](https://www.together.ai/pricing)
