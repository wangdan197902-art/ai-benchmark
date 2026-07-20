---
title: "GLM-4 Flash：完整基准性能指南"
description: "深入分析 GLM-4 Flash 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-flash"
vendor: "other"
version: "glm-4-flash"
tags: ["chinese", "realtime"]
---

# GLM-4 Flash

## 模型概述

清华智谱 GLM-4 Flash 免费模型, 131K 上下文, 速度最快, 适合高并发实时场景。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-flash | 2024-08-12 | 131K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 80.0 | % | 5-shot |
| HumanEval | 67.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 78.4 | % | 0-shot CoT |
| MATH | 39.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 70.5 | % | 3-shot CoT |
| GPQA | 31.3 | % | 0-shot |
| IFEval | 65.9 | % | prompt_strict |
| ARC | 94.2 | % | challenge |
| MUSR | 56.0 | % | 0-shot |
| WinoGrande | 81.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- MMLU 得分 80.0，知识推理能力强。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [GLM-4 Flash 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-12
- 厂商: Other
