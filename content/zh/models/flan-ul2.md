---
title: "Flan-UL2：完整基准性能指南"
description: "深入分析 Flan-UL2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-03-03
lastmod: 2023-03-03
draft: false
weight: 10
model_id: "flan-ul2"
vendor: "other"
version: "flan-ul2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Flan-UL2

## 模型概述

Google Flan-UL2 20B 指令微调模型, 4K 上下文, 基于 UL2 框架, 适合多任务与零样本推理。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | flan-ul2 | 2023-03-03 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.7 | % | 5-shot |
| HumanEval | 46.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.6 | % | 0-shot CoT |
| MATH | 22.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 49.2 | % | 3-shot CoT |
| GPQA | 27.2 | % | 0-shot |
| IFEval | 55.6 | % | prompt_strict |
| ARC | 88.8 | % | challenge |
| MUSR | 37.2 | % | 0-shot |
| WinoGrande | 76.2 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 58.7，知识推理偏弱。
- HumanEval 46.8，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Flan-UL2 文档地址](https://huggingface.co/models)
- 发布日期: 2023-03-03
- 厂商: Other
