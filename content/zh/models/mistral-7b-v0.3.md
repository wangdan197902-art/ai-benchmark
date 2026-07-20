---
title: "Mistral 7B v0.3：完整基准性能指南"
description: "深入分析 Mistral 7B v0.3 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-22
lastmod: 2024-05-22
draft: false
weight: 10
model_id: "mistral-7b-v0.3"
vendor: "mistral"
version: "7b-v0.3"
tags: ["open-weights", "self-hostable"]
---

# Mistral 7B v0.3

## 模型概述

Mistral 7B v0.3 开源模型, 32K 上下文, 改进 v0.2, 扩展词汇表至 32768, 适合本地部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | 7b-v0.3 | 2024-05-22 | 32K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 72.6 | % | 5-shot |
| HumanEval | 68.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 69.4 | % | 0-shot CoT |
| MATH | 26.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 60.5 | % | 3-shot CoT |
| GPQA | 31.2 | % | 0-shot |
| IFEval | 60.9 | % | prompt_strict |
| ARC | 88.9 | % | challenge |
| MUSR | 48.1 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

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

- [Mistral 7B v0.3 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-05-22
- 厂商: Mistral
