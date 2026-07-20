---
title: "GPT-4 0125 Preview：完整基准性能指南"
description: "深入分析 GPT-4 0125 Preview 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-01-25
lastmod: 2024-01-25
draft: false
weight: 10
model_id: "gpt-4-0125-preview"
vendor: "openai"
version: "4-0125-preview"
tags: ["flagship", "long-context", "tool-use"]
---

# GPT-4 0125 Preview

## 模型概述

OpenAI GPT-4 0125 预览版, 128K 上下文, 修复函数调用重复调用问题, 改进代码生成能力。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-0125-preview | 2024-01-25 | 128K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 82.6 | % | 5-shot |
| HumanEval | 80.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.9 | % | 0-shot CoT |
| MATH | 42.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 78.2 | % | 3-shot CoT |
| GPQA | 46.8 | % | 0-shot |
| IFEval | 71.4 | % | prompt_strict |
| ARC | 95.5 | % | challenge |
| MUSR | 65.8 | % | 0-shot |
| WinoGrande | 86.6 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 82.6，知识推理能力强。
- HumanEval 80.3，代码生成能力出色。
- 上下文窗口 128K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 0125 Preview 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2024-01-25
- 厂商: Openai
