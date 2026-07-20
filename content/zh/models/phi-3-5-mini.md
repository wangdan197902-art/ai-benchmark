---
title: "Phi-3.5 Mini：完整基准性能指南"
description: "深入分析 Phi-3.5 Mini 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-16
lastmod: 2024-08-16
draft: false
weight: 10
model_id: "phi-3-5-mini"
vendor: "other"
version: "phi-3-5-mini"
tags: ["open-weights", "self-hostable", "long-context"]
---

# Phi-3.5 Mini

## 模型概述

Microsoft Phi-3.5 Mini 3.8B 模型, 128K 上下文, 改进多语言与长上下文能力, 适合边缘部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | phi-3-5-mini | 2024-08-16 | 128K | text | text | MIT |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 55.7 | % | 5-shot |
| HumanEval | 44.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 22.1 | % | 0-shot CoT |
| MATH | 9.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 47.5 | % | 3-shot CoT |
| GPQA | 24.4 | % | 0-shot |
| IFEval | 48.7 | % | prompt_strict |
| ARC | 81.5 | % | challenge |
| MUSR | 31.2 | % | 0-shot |
| WinoGrande | 68.6 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 上下文窗口 128K，支持长文本。

## 劣势

- MMLU 仅 55.7，知识推理偏弱。
- HumanEval 44.0，代码能力较弱。
- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要

## 参考文献

- [Phi-3.5 Mini 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-16
- 厂商: Other
