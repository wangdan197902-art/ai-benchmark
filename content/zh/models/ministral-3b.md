---
title: "Ministral 3B：完整基准性能指南"
description: "深入分析 Ministral 3B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-10-16
lastmod: 2024-10-16
draft: false
weight: 10
model_id: "ministral-3b"
vendor: "mistral"
version: "ministral-3b"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Ministral 3B

## 模型概述

Mistral Ministral 3B 超轻量边缘模型, 128K 上下文, 3B 参数, 最具性价比的边缘部署模型。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | ministral-3b | 2024-10-16 | 128K | text | text | Mistral Research License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 42.4 | % | 5-shot |
| HumanEval | 37.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 32.2 | % | 0-shot CoT |
| MATH | 10.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 50.1 | % | 3-shot CoT |
| GPQA | 19.0 | % | 0-shot |
| IFEval | 47.8 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 29.4 | % | 0-shot |
| WinoGrande | 64.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 128K，支持长文本。

## 劣势

- MMLU 仅 42.4，知识推理偏弱。
- HumanEval 37.2，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Ministral 3B 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-10-16
- 厂商: Mistral
