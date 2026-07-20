---
title: "Claude 2.1：完整基准性能指南"
description: "深入分析 Claude 2.1 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-21
lastmod: 2023-11-21
draft: false
weight: 10
model_id: "claude-2.1"
vendor: "anthropic"
version: "2.1"
tags: ["legacy", "long-context"]
---

# Claude 2.1

## 模型概述

Anthropic Claude 2.1, 200K 上下文, 相比 2.0 减少 2 倍幻觉率, 改进长文档召回能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 2.1 | 2023-11-21 | 200K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.9 | % | 5-shot |
| HumanEval | 28.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 45.7 | % | 0-shot CoT |
| MATH | 15.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.8 | % | 3-shot CoT |
| GPQA | 26.4 | % | 0-shot |
| IFEval | 55.0 | % | prompt_strict |
| ARC | 84.8 | % | challenge |
| MUSR | 37.7 | % | 0-shot |
| WinoGrande | 67.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 200K，支持长文本。

## 劣势

- HumanEval 28.1，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Claude 2.1 文档地址](https://docs.anthropic.com/claude/docs)
- 发布日期: 2023-11-21
- 厂商: Anthropic
