---
title: "DeepSeek Coder V2：完整基准性能指南"
description: "深入分析 DeepSeek Coder V2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-06-21
lastmod: 2024-06-21
draft: false
weight: 10
model_id: "deepseek-coder-v2"
vendor: "deepseek"
version: "coder-v2"
tags: ["open-weights", "coding", "moe"]
---

# DeepSeek Coder V2

## 模型概述

DeepSeek Coder V2 代码专用 MoE 模型, 128K 上下文, 支持 338 种编程语言, 代码生成能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-v2 | 2024-06-21 | 128K | text | text | DeepSeek License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.3 | % | 5-shot |
| HumanEval | 88.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 62.9 | % | 0-shot CoT |
| MATH | 38.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.3 | % | 3-shot CoT |
| GPQA | 25.4 | % | 0-shot |
| IFEval | 56.7 | % | prompt_strict |
| ARC | 88.5 | % | challenge |
| MUSR | 40.3 | % | 0-shot |
| WinoGrande | 78.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- HumanEval 88.9，代码生成能力出色。
- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [DeepSeek Coder V2 文档地址](https://api-docs.deepseek.com/)
- 发布日期: 2024-06-21
- 厂商: Deepseek
