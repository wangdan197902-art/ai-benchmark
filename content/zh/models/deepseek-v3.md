---
title: "DeepSeek V3：完整基准性能指南"
description: "深入分析 DeepSeek V3 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与自托管考量。"
date: 2024-12-26
lastmod: 2024-12-26
draft: false
weight: 70
model_id: "deepseek-v3"
vendor: "deepseek"
version: "v3"
tags: ["开源权重", "MoE", "中文"]
---

# DeepSeek V3

## 模型概述

DeepSeek V3 是 DeepSeek 于 2024 年 12 月 26 日发布的开源权重混合专家旗舰模型。架构总参数 671B、每 token 激活 37B，训练数据达 14.8 万亿 token。DeepSeek V3 以极低的价格提供前沿级性能——API 定价 $0.27/$1.10 每百万 token，约为同级闭源旗舰的十分之一。模型在 MMLU（88.5 vs 88.7）与 BBH（84.9 vs 83.1）上与 GPT-4o 接近或反超，支持 64K 上下文窗口。模型以较为宽松的 DeepSeek License 发布，迅速成为成本敏感型生产部署的首选，尤其在中文与中英双语场景中。模型还引入了多头潜在注意力（MLA），显著提升长上下文推理效率。

## 核心规格

| 属性 | 数值 |
|------|------|
| 厂商 | DeepSeek |
| 版本 | v3 |
| 发布日期 | 2024-12-26 |
| 上下文窗口 | 64,000 tokens |
| 输入模态 | 文本 |
| 输出模态 | 文本 |
| 许可证 | DeepSeek License |
| 文档地址 | https://api-docs.deepseek.com/ |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU | 88.5 | % | 5-shot |
| HumanEval | 82.6 | pass@1 | — |
| GSM8K | 89.3 | % | 0-shot CoT |
| MATH | 61.6 | % | 0-shot CoT |
| BBH | 84.9 | % | 3-shot CoT |

## 定价

| 档位 | 价格（每百万 token） |
|------|---------------------|
| 输入 | $0.27 |
| 输出 | $1.10 |
| 缓存读取 | $0.07 |
| 缓存写入 | $0.27 |

定价来源：https://api-docs.deepseek.com/quick_start/pricing （截至 2024-12-26）。DeepSeek License 亦允许自托管。

## 优势

- 前沿级性能，成本约为闭源旗舰的 10%。
- 开源权重，可自托管与定制。
- 中英文双语能力突出。
- 高效 MoE 架构 + MLA，长上下文推理效率高。

## 劣势

- 64K 上下文窗口短于 Llama 3.1 405B（128K）与 Qwen2.5 72B（131K）。
- 厂商生态与工具链成熟度不及 Meta/Mistral 等老牌开源厂商。
- 671B 参数体量使自托管对 GPU 资源要求较高。

## 适用场景

- 高吞吐生产部署，API 成本是首要约束。
- 中英双语客服与内容生成。
- 需要 MMLU/BBH 级能力的推理密集型应用。
- 需要权重级访问前沿 MoE 模型的研究项目。

## 参考文献

- [DeepSeek V3 GitHub 仓库](https://github.com/deepseek-ai/DeepSeek-V3)
- [DeepSeek API 定价](https://api-docs.deepseek.com/quick_start/pricing)
- [DeepSeek API 文档](https://api-docs.deepseek.com/)
