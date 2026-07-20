---
title: "DeepSeek V2：完整基准性能指南"
description: "深入分析 DeepSeek V2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-07
lastmod: 2024-05-07
draft: false
weight: 10
model_id: "deepseek-v2"
vendor: "deepseek"
version: "v2"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2

## 模型概述

DeepSeek V2 开源 MoE 模型, 总参 236B/活跃 21B, 32K 上下文, 首创 MLA 注意力机制, 性价比突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2 | 2024-05-07 | 32K | text | text | DeepSeek License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.2 | % | 5-shot |
| HumanEval | 75.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 35.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.5 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 78.6 | % | prompt_strict |
| ARC | 92.1 | % | challenge |
| MUSR | 53.4 | % | 0-shot |
| WinoGrande | 84.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [DeepSeek V2 文档地址](https://api-docs.deepseek.com/)
- 发布日期: 2024-05-07
- 厂商: Deepseek
