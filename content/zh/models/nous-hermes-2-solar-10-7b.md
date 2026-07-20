---
title: "Nous Hermes 2 Solar 10.7B：完整基准性能指南"
description: "深入分析 Nous Hermes 2 Solar 10.7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-19
lastmod: 2024-02-19
draft: false
weight: 10
model_id: "nous-hermes-2-solar-10-7b"
vendor: "other"
version: "nous-hermes-2-solar-10-7b"
tags: ["open-weights", "self-hostable"]
---

# Nous Hermes 2 Solar 10.7B

## 模型概述

NousResearch Hermes 2 Solar 10.7B 微调模型, 4K 上下文, 基于 Solar 10.7B, 性能接近 Llama 2 70B。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | nous-hermes-2-solar-10-7b | 2024-02-19 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 63.4 | % | 5-shot |
| HumanEval | 59.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 59.6 | % | 0-shot CoT |
| MATH | 37.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.8 | % | 3-shot CoT |
| GPQA | 35.9 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 85.9 | % | challenge |
| MUSR | 39.6 | % | 0-shot |
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
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Nous Hermes 2 Solar 10.7B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-02-19
- 厂商: Other
