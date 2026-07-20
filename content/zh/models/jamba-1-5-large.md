---
title: "Jamba 1.5 Large：完整基准性能指南"
description: "深入分析 Jamba 1.5 Large 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-07
lastmod: 2024-08-07
draft: false
weight: 10
model_id: "jamba-1-5-large"
vendor: "other"
version: "jamba-1-5-large"
tags: ["open-weights", "moe", "long-context"]
---

# Jamba 1.5 Large

## 模型概述

AI21 Labs Jamba 1.5 Large 混合 SSM-Transformer 模型, 256K 上下文, 总参 398B/活跃 94B, 长上下文突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | jamba-1-5-large | 2024-08-07 | 256K | text | text | Jamba Open Model License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 73.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 60.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 82.8 | % | 3-shot CoT |
| GPQA | 50.8 | % | 0-shot |
| IFEval | 70.8 | % | prompt_strict |
| ARC | 93.8 | % | challenge |
| MUSR | 51.1 | % | 0-shot |
| WinoGrande | 84.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 84.3，知识推理能力强。
- 上下文窗口 256K，支持长文本。
- 采用 MoE 混合专家架构。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要

## 参考文献

- [Jamba 1.5 Large 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-07
- 厂商: Other
