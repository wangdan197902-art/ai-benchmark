---
title: "Gemini 2.0 Flash Thinking：完整基准性能指南"
description: "深入分析 Gemini 2.0 Flash Thinking 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-12-19
lastmod: 2024-12-19
draft: false
weight: 10
model_id: "gemini-2-0-flash-thinking"
vendor: "google"
version: "2.0-flash-thinking"
tags: ["flagship", "reasoning", "multimodal"]
---

# Gemini 2.0 Flash Thinking

## 模型概述

Google Gemini 2.0 Flash Thinking 实验版, 1M 上下文, 链式思维推理, 在数学与编码上接近 o1。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 2.0-flash-thinking | 2024-12-19 | 1048K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 86.5 | % | 5-shot |
| HumanEval | 87.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 91.3 | % | 0-shot CoT |
| MATH | 56.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 87.9 | % | 3-shot CoT |
| GPQA | 61.0 | % | 0-shot |
| IFEval | 82.8 | % | prompt_strict |
| ARC | 95.0 | % | challenge |
| MUSR | 70.8 | % | 0-shot |
| WinoGrande | 88.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 86.5，知识推理能力强。
- HumanEval 87.2，代码生成能力出色。
- GSM8K 91.3，数学推理稳健。
- 支持文本、图像、音频多模态输入。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [Gemini 2.0 Flash Thinking 文档地址](https://ai.google.dev/gemini-api/docs)
- 发布日期: 2024-12-19
- 厂商: Google
