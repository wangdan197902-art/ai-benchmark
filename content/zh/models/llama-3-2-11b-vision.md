---
title: "Llama 3.2 11B Vision：完整基准性能指南"
description: "深入分析 Llama 3.2 11B Vision 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-09-25
lastmod: 2024-09-25
draft: false
weight: 10
model_id: "llama-3-2-11b-vision"
vendor: "meta"
version: "3.2-11b-vision"
tags: ["open-weights", "multimodal", "self-hostable"]
---

# Llama 3.2 11B Vision

## 模型概述

Meta Llama 3.2 11B Vision 经济型多模态开源模型, 128K 上下文, 11B 参数, 适合边缘视觉任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | 3.2-11b-vision | 2024-09-25 | 128K | text, image | text | Llama 3.2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 61.9 | % | 5-shot |
| HumanEval | 50.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 68.2 | % | 0-shot CoT |
| MATH | 29.9 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 69.1 | % | 3-shot CoT |
| GPQA | 35.5 | % | 0-shot |
| IFEval | 58.4 | % | prompt_strict |
| ARC | 86.0 | % | challenge |
| MUSR | 41.7 | % | 0-shot |
| WinoGrande | 72.7 | % | 0-shot |

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

- 视觉与图像理解

## 参考文献

- [Llama 3.2 11B Vision 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2024-09-25
- 厂商: Meta
