---
title: "Llemma 7B：完整基准性能指南"
description: "深入分析 Llemma 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-10-17
lastmod: 2023-10-17
draft: false
weight: 10
model_id: "llemma-7b"
vendor: "other"
version: "llemma-7b"
tags: ["open-weights", "math", "self-hostable"]
---

# Llemma 7B

## 模型概述

TheBloke Llemma 7B 数学专用模型, 4K 上下文, 基于 Code Llama 7B 继续训练, 数学推理能力突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | llemma-7b | 2023-10-17 | 4K | text | text | Apache 2.0 |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 66.0 | % | 5-shot |
| HumanEval | 64.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.9 | % | 0-shot CoT |
| MATH | 47.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 73.1 | % | 3-shot CoT |
| GPQA | 37.4 | % | 0-shot |
| IFEval | 52.9 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 42.6 | % | 0-shot |
| WinoGrande | 70.8 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [Llemma 7B 文档地址](https://huggingface.co/models)
- 发布日期: 2023-10-17
- 厂商: Other
