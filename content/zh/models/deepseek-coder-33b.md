---
title: "DeepSeek Coder 33B：完整基准性能指南"
description: "深入分析 DeepSeek Coder 33B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "deepseek-coder-33b"
vendor: "deepseek"
version: "coder-33b"
tags: ["open-weights", "coding", "self-hostable"]
---

# DeepSeek Coder 33B

## 模型概述

DeepSeek Coder 33B 代码专用开源模型, 16K 上下文, 33B 参数, 性能接近 GPT-3.5, 开源代码模型旗舰。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | coder-33b | 2024-01-25 | 16K | text | text | DeepSeek License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 65.9 | % | 5-shot |
| HumanEval | 71.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.7 | % | 0-shot CoT |
| MATH | 32.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 61.6 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 58.8 | % | prompt_strict |
| ARC | 92.2 | % | challenge |
| MUSR | 45.8 | % | 0-shot |
| WinoGrande | 79.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [DeepSeek Coder 33B 文档地址](https://api-docs.deepseek.com/)
- 发布日期: 2024-01-25
- 厂商: Deepseek
