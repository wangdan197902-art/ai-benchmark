---
title: "Mistral Large：完整基准性能指南"
description: "深入分析 Mistral Large 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-26
lastmod: 2024-02-26
draft: false
weight: 10
model_id: "mistral-large"
vendor: "mistral"
version: "large"
tags: ["flagship", "eu-residency"]
---

# Mistral Large

## 模型概述

Mistral AI Large 首代旗舰, 32K 上下文, 多语言与推理能力突出, 原生支持函数调用与 JSON 输出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | large | 2024-02-26 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.0 | % | 5-shot |
| HumanEval | 73.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 80.9 | % | 0-shot CoT |
| MATH | 49.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 76.7 | % | 3-shot CoT |
| GPQA | 38.1 | % | 0-shot |
| IFEval | 75.8 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 52.1 | % | 0-shot |
| WinoGrande | 83.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 82.0，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- Agent 工作流与工具调用

## 参考文献

- [Mistral Large 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-02-26
- 厂商: Mistral
