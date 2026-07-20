---
title: "GPT-4 Vision Preview：完整基准性能指南"
description: "深入分析 GPT-4 Vision Preview 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-09-25
lastmod: 2023-09-25
draft: false
weight: 10
model_id: "gpt-4-vision-preview"
vendor: "openai"
version: "4-vision-preview"
tags: ["multimodal", "flagship"]
---

# GPT-4 Vision Preview

## 模型概述

OpenAI GPT-4 Vision 预览版, 支持图像输入理解, 128K 上下文, 多模态能力首次集成。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Openai | 4-vision-preview | 2023-09-25 | 128K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 85.0 | % | 5-shot |
| HumanEval | 70.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.5 | % | 0-shot CoT |
| MATH | 49.7 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.0 | % | 3-shot CoT |
| GPQA | 36.3 | % | 0-shot |
| IFEval | 72.7 | % | prompt_strict |
| ARC | 94.6 | % | challenge |
| MUSR | 64.5 | % | 0-shot |
| WinoGrande | 80.6 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 85.0，知识推理能力强。
- 支持文本、图像、音频多模态输入。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [GPT-4 Vision Preview 文档地址](https://platform.openai.com/docs/models)
- 发布日期: 2023-09-25
- 厂商: Openai
