---
title: "Mistral 7B v0.2：完整基准性能指南"
description: "深入分析 Mistral 7B v0.2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-03-23
lastmod: 2024-03-23
draft: false
weight: 10
model_id: "mistral-7b-v0.2"
vendor: "mistral"
version: "7b-v0.2"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.2

## 模型概述

Mistral 7B v0.2 开源模型, 32K 上下文, 扩展上下文窗口, 改进推理, 适合通用任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.2 | 2024-03-23 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 64.4 | % | 5-shot |
| HumanEval | 59.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 56.2 | % | 0-shot CoT |
| MATH | 25.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.3 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 59.2 | % | prompt_strict |
| ARC | 85.5 | % | challenge |
| MUSR | 36.7 | % | 0-shot |
| WinoGrande | 71.7 | % | 0-shot |

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

- 通用对话与问答

## 参考文献

- [Mistral 7B v0.2 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-03-23
- 厂商: Mistral
