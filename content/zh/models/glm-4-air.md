---
title: "GLM-4 Air：完整基准性能指南"
description: "深入分析 GLM-4 Air 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-08-12
lastmod: 2024-08-12
draft: false
weight: 10
model_id: "glm-4-air"
vendor: "other"
version: "glm-4-air"
tags: ["chinese", "realtime"]
---

# GLM-4 Air

## 模型概述

清华智谱 GLM-4 Air 经济型模型, 131K 上下文, 速度快成本低, 适合大规模部署。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | glm-4-air | 2024-08-12 | 131K | text | text | Proprietary |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.9 | % | 5-shot |
| HumanEval | 68.3 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 82.3 | % | 0-shot CoT |
| MATH | 40.6 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 79.0 | % | 3-shot CoT |
| GPQA | 31.3 | % | 0-shot |
| IFEval | 75.7 | % | prompt_strict |
| ARC | 92.3 | % | challenge |
| MUSR | 46.7 | % | 0-shot |
| WinoGrande | 78.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。

## 适用场景

- 通用对话与问答

## 参考文献

- [GLM-4 Air 文档地址](https://huggingface.co/models)
- 发布日期: 2024-08-12
- 厂商: Other
