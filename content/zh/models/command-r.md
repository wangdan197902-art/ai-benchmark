---
title: "Command R：完整基准性能指南"
description: "深入分析 Command R 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-11
lastmod: 2024-03-11
draft: false
weight: 10
model_id: "command-r"
vendor: "cohere"
version: "r"
tags: ["rag", "enterprise", "tool-use"]
---

# Command R

## 模型概述

Cohere Command R 经济型 35B 模型, 128K 上下文, 针对 RAG 与工具调用优化, 适合大规模部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Cohere | r | 2024-03-11 | 128K | text | text | CC-BY-NC-4.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 79.3 | % | 5-shot |
| HumanEval | 75.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.9 | % | 0-shot CoT |
| MATH | 43.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.4 | % | 3-shot CoT |
| GPQA | 44.0 | % | 0-shot |
| IFEval | 74.1 | % | prompt_strict |
| ARC | 93.9 | % | challenge |
| MUSR | 57.0 | % | 0-shot |
| WinoGrande | 84.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- GSM8K 86.9，数学推理稳健。
- 企业级合规认证。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 企业客户支持

## 参考文献

- [Command R 文档地址](https://docs.cohere.com/docs)
- 发布日期: 2024-03-11
- 厂商: Cohere
