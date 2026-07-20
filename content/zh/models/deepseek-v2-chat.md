---
title: "DeepSeek V2 Chat：完整基准性能指南"
description: "深入分析 DeepSeek V2 Chat 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-06-17
lastmod: 2024-06-17
draft: false
weight: 10
model_id: "deepseek-v2-chat"
vendor: "deepseek"
version: "v2-chat"
tags: ["open-weights", "moe", "chinese"]
---

# DeepSeek V2 Chat

## 模型概述

DeepSeek V2 Chat 对话版本, 32K 上下文, 针对对话场景优化, 适合聊天助手与客服应用。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Deepseek | v2-chat | 2024-06-17 | 32K | text | text | DeepSeek License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 67.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 77.4 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 38.3 | % | 0-shot |
| IFEval | 71.5 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 52.0 | % | 0-shot |
| WinoGrande | 80.2 | % | 0-shot |

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

- 通用对话与问答

## 参考文献

- [DeepSeek V2 Chat 文档地址](https://api-docs.deepseek.com/)
- 发布日期: 2024-06-17
- 厂商: Deepseek
