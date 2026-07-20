---
title: "Command R+ (08-2024)：完整基准性能指南"
description: "深入分析 Command R+ (08-2024) 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "command-r-plus-08-2024"
vendor: "cohere"
version: "r-plus-08-2024"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R+ (08-2024)

## 模型概述

Cohere Command R+ 08-2024 版本, 128K 上下文, 改进代码生成与多语言能力, 性能接近 GPT-4。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r-plus-08-2024 | 2024-08-13 | 128K | text | text | CC-BY-NC-4.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.3 | % | 5-shot |
| HumanEval | 75.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.8 | % | 0-shot CoT |
| MATH | 43.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.1 | % | 3-shot CoT |
| GPQA | 38.7 | % | 0-shot |
| IFEval | 72.1 | % | prompt_strict |
| ARC | 93.4 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 83.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 82.3，知识推理能力强。
- 企业级合规认证。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 企业客户支持

## 参考文献

- [Command R+ (08-2024) 文档地址](https://docs.cohere.com/docs)
- 发布日期: 2024-08-13
- 厂商: Cohere
