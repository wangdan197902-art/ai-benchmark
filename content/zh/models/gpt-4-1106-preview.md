---
title: "GPT-4 1106 Preview：完整基准性能指南"
description: "深入分析 GPT-4 1106 Preview 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-11-06
lastmod: 2023-11-06
draft: false
weight: 10
model_id: "gpt-4-1106-preview"
vendor: "openai"
version: "4-1106-preview"
tags: ["flagship", "long-context", "tool-use"]
---

# GPT-4 1106 Preview

## 模型概述

OpenAI GPT-4 1106 预览版, 128K 上下文, 改进函数调用与 JSON 模式, 适合结构化输出任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-1106-preview | 2023-11-06 | 128K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.8 | % | 5-shot |
| HumanEval | 83.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 85.4 | % | 0-shot CoT |
| MATH | 52.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 80.0 | % | 3-shot CoT |
| GPQA | 36.2 | % | 0-shot |
| IFEval | 73.9 | % | prompt_strict |
| ARC | 94.3 | % | challenge |
| MUSR | 58.4 | % | 0-shot |
| WinoGrande | 82.0 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 81.8，知识推理能力强。
- HumanEval 83.7，代码生成能力出色。
- GSM8K 85.4，数学推理稳健。
- 上下文窗口 128K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 长文档摘要
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 1106 Preview 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-11-06
- 厂商: Openai
