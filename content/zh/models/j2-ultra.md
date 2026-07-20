---
title: "Jurassic-2 Ultra：完整基准性能指南"
description: "深入分析 Jurassic-2 Ultra 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-01-12
lastmod: 2023-01-12
draft: false
weight: 10
model_id: "j2-ultra"
vendor: "other"
version: "j2-ultra"
tags: ["legacy", "flagship"]
---

# Jurassic-2 Ultra

## 模型概述

AI21 Labs Jurassic-2 Ultra 旗舰模型, 8K 上下文, 在 J2 系列中性能最强, 适合复杂推理任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | j2-ultra | 2023-01-12 | 8K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 62.5 | % | 5-shot |
| HumanEval | 50.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 30.3 | % | 0-shot CoT |
| MATH | 27.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 52.9 | % | 3-shot CoT |
| GPQA | 28.7 | % | 0-shot |
| IFEval | 47.9 | % | prompt_strict |
| ARC | 82.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 74.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- Agent 工作流与工具调用

## 参考文献

- [Jurassic-2 Ultra 文档地址](https://huggingface.co/models)
- 发布日期: 2023-01-12
- 厂商: Other
