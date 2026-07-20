---
title: "Grok-2 Vision：完整基准性能指南"
description: "深入分析 Grok-2 Vision 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-13
lastmod: 2024-08-13
draft: false
weight: 10
model_id: "grok-2-vision"
vendor: "xai"
version: "2-vision"
tags: ["multimodal"]
---

# Grok-2 Vision

## 模型概述

xAI Grok-2 Vision 多模态模型, 32K 上下文, 支持图像理解, 适合视觉问答与多模态推理。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Xai | 2-vision | 2024-08-13 | 32K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 83.4 | % | 5-shot |
| HumanEval | 84.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 83.4 | % | 0-shot CoT |
| MATH | 41.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 75.4 | % | 3-shot CoT |
| GPQA | 43.8 | % | 0-shot |
| IFEval | 76.9 | % | prompt_strict |
| ARC | 93.3 | % | challenge |
| MUSR | 57.7 | % | 0-shot |
| WinoGrande | 87.5 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 83.4，知识推理能力强。
- HumanEval 84.2，代码生成能力出色。
- 支持文本、图像、音频多模态输入。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 视觉与图像理解

## 参考文献

- [Grok-2 Vision 文档地址](https://docs.x.ai/)
- 发布日期: 2024-08-13
- 厂商: Xai
