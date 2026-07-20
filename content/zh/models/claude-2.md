---
title: "Claude 2：完整基准性能指南"
description: "深入分析 Claude 2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-07-11
lastmod: 2023-07-11
draft: false
weight: 10
model_id: "claude-2"
vendor: "anthropic"
version: "2"
tags: ["legacy", "long-context"]
---

# Claude 2

## 模型概述

Anthropic Claude 2, 100K 上下文, 在编码/数学/推理上超越 Claude 1.3, 首次开放 API。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Anthropic | 2 | 2023-07-11 | 100K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 66.3 | % | 5-shot |
| HumanEval | 31.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.5 | % | 0-shot CoT |
| MATH | 21.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.2 | % | 3-shot CoT |
| GPQA | 31.4 | % | 0-shot |
| IFEval | 55.0 | % | prompt_strict |
| ARC | 80.4 | % | challenge |
| MUSR | 35.2 | % | 0-shot |
| WinoGrande | 66.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 100K，支持长文本。

## 劣势

- HumanEval 31.7，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Claude 2 文档地址](https://docs.anthropic.com/claude/docs)
- 发布日期: 2023-07-11
- 厂商: Anthropic
