---
title: "Gemini 1.5 Flash 002：完整基准性能指南"
description: "深入分析 Gemini 1.5 Flash 002 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-24
lastmod: 2024-09-24
draft: false
weight: 10
model_id: "gemini-1-5-flash-002"
vendor: "google"
version: "1.5-flash-002"
tags: ["multimodal", "realtime", "long-context"]
---

# Gemini 1.5 Flash 002

## 模型概述

Google Gemini 1.5 Flash 002 生产版本, 1M 上下文, 改进质量与稳定性。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Google | 1.5-flash-002 | 2024-09-24 | 1000K | text, image, audio, video | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 81.1 | % | 5-shot |
| HumanEval | 66.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.8 | % | 0-shot CoT |
| MATH | 40.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.8 | % | 3-shot CoT |
| GPQA | 32.0 | % | 0-shot |
| IFEval | 77.2 | % | prompt_strict |
| ARC | 91.8 | % | challenge |
| MUSR | 59.8 | % | 0-shot |
| WinoGrande | 81.9 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 81.1，知识推理能力强。
- 支持文本、图像、音频多模态输入。
- 上下文窗口 1000K，支持长文本。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 长文档摘要
- 视觉与图像理解

## 参考文献

- [Gemini 1.5 Flash 002 文档地址](https://ai.google.dev/gemini-api/docs)
- 发布日期: 2024-09-24
- 厂商: Google
