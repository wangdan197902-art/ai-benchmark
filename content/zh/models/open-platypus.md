---
title: "Open-Platypus：完整基准性能指南"
description: "深入分析 Open-Platypus 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-09-15
lastmod: 2023-09-15
draft: false
weight: 10
model_id: "open-platypus"
vendor: "other"
version: "open-platypus"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Open-Platypus

## 模型概述

Garage bAInd Open-Platypus 数据集与模型, 2K 上下文, 基于 Llama 2 微调, 适合 STEM 推理任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | open-platypus | 2023-09-15 | 2K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 68.7 | % | 5-shot |
| HumanEval | 48.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 43.9 | % | 0-shot CoT |
| MATH | 21.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 63.7 | % | 3-shot CoT |
| GPQA | 34.9 | % | 0-shot |
| IFEval | 46.0 | % | prompt_strict |
| ARC | 80.1 | % | challenge |
| MUSR | 40.0 | % | 0-shot |
| WinoGrande | 66.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- HumanEval 48.2，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Open-Platypus 文档地址](https://huggingface.co/models)
- 发布日期: 2023-09-15
- 厂商: Other
