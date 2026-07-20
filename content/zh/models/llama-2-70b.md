---
title: "Llama 2 70B：完整基准性能指南"
description: "深入分析 Llama 2 70B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-07-18
lastmod: 2023-07-18
draft: false
weight: 10
model_id: "llama-2-70b"
vendor: "meta"
version: "2-70b"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Llama 2 70B

## 模型概述

Meta Llama 2 70B 开源模型, 4K 上下文, 在开源模型中领先, 商用许可, 适合企业自托管。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 2-70b | 2023-07-18 | 4K | text | text | Llama 2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 53.0 | % | 5-shot |
| HumanEval | 50.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 51.8 | % | 0-shot CoT |
| MATH | 22.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.5 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 57.1 | % | prompt_strict |
| ARC | 80.3 | % | challenge |
| MUSR | 36.1 | % | 0-shot |
| WinoGrande | 73.4 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 53.0，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Llama 2 70B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2023-07-18
- 厂商: Meta
