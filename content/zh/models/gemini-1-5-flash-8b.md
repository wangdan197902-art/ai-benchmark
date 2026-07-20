---
title: "Gemini 1.5 Flash-8B：完整基准性能指南"
description: "深入分析 Gemini 1.5 Flash-8B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-10-03
lastmod: 2024-10-03
draft: false
weight: 10
model_id: "gemini-1-5-flash-8b"
vendor: "google"
version: "1.5-flash-8b"
tags: ["multimodal", "realtime"]
---

# Gemini 1.5 Flash-8B

## 模型概述

Google Gemini 1.5 Flash-8B 8B 参数经济型, 1M 上下文, 更低延迟, 适合高频实时多模态任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-8b | 2024-10-03 | 1000K | text, image, audio, video | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 76.6 | % | 5-shot |
| HumanEval | 70.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.5 | % | 0-shot CoT |
| MATH | 35.0 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 74.8 | % | 3-shot CoT |
| GPQA | 35.0 | % | 0-shot |
| IFEval | 68.1 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 45.6 | % | 0-shot |
| WinoGrande | 79.7 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 支持文本、图像、音频多模态输入。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 视觉与图像理解

## 参考文献

- [Gemini 1.5 Flash-8B 文档地址](https://ai.google.dev/gemini-api/docs)
- 发布日期: 2024-10-03
- 厂商: Google
