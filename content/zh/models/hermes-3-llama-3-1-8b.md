---
title: "Hermes 3 Llama 3.1 8B：完整基准性能指南"
description: "深入分析 Hermes 3 Llama 3.1 8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "hermes-3-llama-3-1-8b"
vendor: "other"
version: "hermes-3-llama-3-1-8b"
tags: ["open-weights", "self-hostable"]
---

# Hermes 3 Llama 3.1 8B

## 模型概述

NousResearch Hermes 3 Llama 3.1 8B 微调模型, 131K 上下文, 经济型开源模型, 适合本地部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | hermes-3-llama-3-1-8b | 2024-08-12 | 131K | text | text | Llama 3.1 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.1 | % | 5-shot |
| HumanEval | 67.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 72.9 | % | 0-shot CoT |
| MATH | 25.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.6 | % | 3-shot CoT |
| GPQA | 31.5 | % | 0-shot |
| IFEval | 60.7 | % | prompt_strict |
| ARC | 88.7 | % | challenge |
| MUSR | 38.0 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

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

- [Hermes 3 Llama 3.1 8B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-12
- 厂商: Other
