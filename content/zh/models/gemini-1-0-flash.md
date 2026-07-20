---
title: "Gemini 1.0 Flash：完整基准性能指南"
description: "深入分析 Gemini 1.0 Flash 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-15
lastmod: 2024-02-15
draft: false
weight: 10
model_id: "gemini-1-0-flash"
vendor: "google"
version: "1.0-flash"
tags: ["realtime", "legacy"]
---

# Gemini 1.0 Flash

## 模型概述

Google Gemini 1.0 Flash 经济型, 32K 上下文, 速度快成本低, 适合实时多模态应用。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.0-flash | 2024-02-15 | 32K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.7 | % | 5-shot |
| HumanEval | 65.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 86.2 | % | 0-shot CoT |
| MATH | 39.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.8 | % | 3-shot CoT |
| GPQA | 37.7 | % | 0-shot |
| IFEval | 71.8 | % | prompt_strict |
| ARC | 92.6 | % | challenge |
| MUSR | 55.9 | % | 0-shot |
| WinoGrande | 80.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- GSM8K 86.2，数学推理稳健。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [Gemini 1.0 Flash 文档地址](https://ai.google.dev/gemini-api/docs)
- 发布日期: 2024-02-15
- 厂商: Google
