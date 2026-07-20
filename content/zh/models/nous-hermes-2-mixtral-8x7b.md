---
title: "Nous Hermes 2 Mixtral 8x7B：完整基准性能指南"
description: "深入分析 Nous Hermes 2 Mixtral 8x7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-mixtral-8x7b"
vendor: "other"
version: "nous-hermes-2-mixtral-8x7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Mixtral 8x7B

## 模型概述

NousResearch Hermes 2 Mixtral 8x7B 微调模型, 32K 上下文, 基于 Mixtral 8x7B, 改进指令遵循能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-mixtral-8x7b | 2024-02-19 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.4 | % | 5-shot |
| HumanEval | 78.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.5 | % | 0-shot CoT |
| MATH | 42.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 72.4 | % | 3-shot CoT |
| GPQA | 35.1 | % | 0-shot |
| IFEval | 75.3 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 57.4 | % | 0-shot |
| WinoGrande | 82.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 81.4，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试

## 参考文献

- [Nous Hermes 2 Mixtral 8x7B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-02-19
- 厂商: Other
