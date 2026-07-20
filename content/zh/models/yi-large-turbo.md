---
title: "Yi Large Turbo：完整基准性能指南"
description: "深入分析 Yi Large Turbo 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-07-24
lastmod: 2024-07-24
draft: false
weight: 10
model_id: "yi-large-turbo"
vendor: "other"
version: "yi-large-turbo"
tags: ["flagship", "chinese", "realtime"]
---

# Yi Large Turbo

## 模型概述

01.AI Yi Large Turbo 经济型旗舰, 16K 上下文, 速度快成本低, 性能接近 Yi Large。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | yi-large-turbo | 2024-07-24 | 16K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.4 | % | 5-shot |
| HumanEval | 72.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.0 | % | 0-shot CoT |
| MATH | 42.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.4 | % | 3-shot CoT |
| GPQA | 38.2 | % | 0-shot |
| IFEval | 70.7 | % | prompt_strict |
| ARC | 95.6 | % | challenge |
| MUSR | 63.7 | % | 0-shot |
| WinoGrande | 82.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 84.4，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 代码生成与调试
- Agent 工作流与工具调用

## 参考文献

- [Yi Large Turbo 文档地址](https://huggingface.co/models)
- 发布日期: 2024-07-24
- 厂商: Other
