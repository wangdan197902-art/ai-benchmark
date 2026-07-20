---
title: "Grok Beta：完整基准性能指南"
description: "深入分析 Grok Beta 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-04
lastmod: 2023-11-04
draft: false
weight: 10
model_id: "grok-beta"
vendor: "xai"
version: "beta"
tags: ["legacy", "realtime"]
---

# Grok Beta

## 模型概述

xAI Grok Beta 早期预览版, 8K 上下文, 集成 X 平台实时数据, 幽默风格对话能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | beta | 2023-11-04 | 8K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 51.0 | % | 5-shot |
| HumanEval | 31.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.7 | % | 0-shot CoT |
| MATH | 19.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.2 | % | 3-shot CoT |
| GPQA | 20.6 | % | 0-shot |
| IFEval | 56.2 | % | prompt_strict |
| ARC | 81.7 | % | challenge |
| MUSR | 43.7 | % | 0-shot |
| WinoGrande | 69.2 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 51.0，知识推理偏弱。
- HumanEval 31.0，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 8K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Grok Beta 文档地址](https://docs.x.ai/)
- 发布日期: 2023-11-04
- 厂商: Xai
