---
title: "Phi-3 Mini：完整基准性能指南"
description: "深入分析 Phi-3 Mini 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-04-22
lastmod: 2024-04-22
draft: false
weight: 10
model_id: "phi-3-mini"
vendor: "other"
version: "phi-3-mini"
tags: ["open-weights", "self-hostable"]
---

# Phi-3 Mini

## 模型概述

Microsoft Phi-3 Mini 3.8B 轻量模型, 4K 上下文 (可扩展 128K), 训练数据高质量, 性能超越 Llama 2 7B。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-mini | 2024-04-22 | 4K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 43.6 | % | 5-shot |
| HumanEval | 26.9 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 40.9 | % | 0-shot CoT |
| MATH | 17.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 55.9 | % | 3-shot CoT |
| GPQA | 20.7 | % | 0-shot |
| IFEval | 54.9 | % | prompt_strict |
| ARC | 84.4 | % | challenge |
| MUSR | 33.5 | % | 0-shot |
| WinoGrande | 67.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 43.6，知识推理偏弱。
- HumanEval 26.9，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Phi-3 Mini 文档地址](https://huggingface.co/models)
- 发布日期: 2024-04-22
- 厂商: Other
