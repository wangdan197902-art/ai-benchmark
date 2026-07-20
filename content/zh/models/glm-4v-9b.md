---
title: "GLM-4V 9B：完整基准性能指南"
description: "深入分析 GLM-4V 9B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-06-05
lastmod: 2024-06-05
draft: false
weight: 10
model_id: "glm-4v-9b"
vendor: "other"
version: "glm-4v-9b"
tags: ["open-weights", "chinese", "self-hostable", "multimodal"]
---

# GLM-4V 9B

## 模型概述

清华智谱 GLM-4V 9B 多模态开源模型, 131K 上下文, 9B 参数, 视觉理解能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4v-9b | 2024-06-05 | 131K | text, image | text | GLM-4 License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 73.4 | % | 5-shot |
| HumanEval | 66.0 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 73.5 | % | 0-shot CoT |
| MATH | 33.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 65.1 | % | 3-shot CoT |
| GPQA | 28.3 | % | 0-shot |
| IFEval | 67.4 | % | prompt_strict |
| ARC | 90.2 | % | challenge |
| MUSR | 38.5 | % | 0-shot |
| WinoGrande | 73.1 | % | 0-shot |

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

- [GLM-4V 9B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-06-05
- 厂商: Other
