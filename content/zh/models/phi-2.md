---
title: "Phi-2：完整基准性能指南"
description: "深入分析 Phi-2 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-12-11
lastmod: 2023-12-11
draft: false
weight: 10
model_id: "phi-2"
vendor: "other"
version: "phi-2"
tags: ["open-weights", "self-hostable", "legacy"]
---

# Phi-2

## 模型概述

Microsoft Phi-2 2.7B 模型, 2K 上下文, 在 2.7B 规模上推理能力突出, 适合研究/教育用途。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-2 | 2023-12-11 | 2K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 57.5 | % | 5-shot |
| HumanEval | 39.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 36.8 | % | 0-shot CoT |
| MATH | 20.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.8 | % | 3-shot CoT |
| GPQA | 21.8 | % | 0-shot |
| IFEval | 48.8 | % | prompt_strict |
| ARC | 75.1 | % | challenge |
| MUSR | 23.7 | % | 0-shot |
| WinoGrande | 72.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 57.5，知识推理偏弱。
- HumanEval 39.7，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 2K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Phi-2 文档地址](https://huggingface.co/models)
- 发布日期: 2023-12-11
- 厂商: Other
