---
title: "Llama 3.1 70B：完整基准性能指南"
description: "深入分析 Llama 3.1 70B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-07-23
lastmod: 2024-07-23
draft: false
weight: 10
model_id: "llama-3-1-70b"
vendor: "meta"
version: "3.1-70b"
tags: ["open-weights", "self-hostable"]
---

# Llama 3.1 70B

## 模型概述

Meta Llama 3.1 70B 中端开源模型, 128K 上下文, 性能接近 GPT-4, 推理与编码能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.1-70b | 2024-07-23 | 128K | text | text | Llama 3 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.6 | % | 5-shot |
| HumanEval | 79.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 38.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.2 | % | 3-shot CoT |
| GPQA | 40.0 | % | 0-shot |
| IFEval | 73.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 81.0 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [Llama 3.1 70B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-07-23
- 厂商: Meta
