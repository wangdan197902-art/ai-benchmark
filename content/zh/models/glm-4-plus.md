---
title: "GLM-4 Plus：完整基准性能指南"
description: "深入分析 GLM-4 Plus 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-plus"
vendor: "other"
version: "glm-4-plus"
tags: ["flagship", "chinese", "multimodal"]
---

# GLM-4 Plus

## 模型概述

清华智谱 GLM-4 Plus 旗舰模型, 131K 上下文, 支持文本与图像输入, 中文能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-plus | 2024-08-12 | 131K | text, image | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 84.3 | % | 5-shot |
| HumanEval | 72.7 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 81.8 | % | 0-shot CoT |
| MATH | 53.3 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 83.6 | % | 3-shot CoT |
| GPQA | 35.4 | % | 0-shot |
| IFEval | 79.2 | % | prompt_strict |
| ARC | 94.5 | % | challenge |
| MUSR | 51.3 | % | 0-shot |
| WinoGrande | 85.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 84.3，知识推理能力强。
- 支持文本、图像、音频多模态输入。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 代码生成与调试
- 视觉与图像理解
- Agent 工作流与工具调用

## 参考文献

- [GLM-4 Plus 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-12
- 厂商: Other
