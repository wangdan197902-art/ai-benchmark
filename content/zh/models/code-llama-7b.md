---
title: "Code Llama 7B：完整基准性能指南"
description: "深入分析 Code Llama 7B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2023-08-24
lastmod: 2023-08-24
draft: false
weight: 10
model_id: "code-llama-7b"
vendor: "meta"
version: "code-llama-7b"
tags: ["open-weights", "coding", "self-hostable"]
---

# Code Llama 7B

## 模型概述

Meta Code Llama 7B 代码专用开源模型, 16K 上下文, 7B 参数, 适合本地代码补全与生成。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Meta | code-llama-7b | 2023-08-24 | 16K | text | text | Llama 2 Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 58.5 | % | 5-shot |
| HumanEval | 76.4 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 52.2 | % | 0-shot CoT |
| MATH | 47.1 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 66.9 | % | 3-shot CoT |
| GPQA | 29.5 | % | 0-shot |
| IFEval | 61.2 | % | prompt_strict |
| ARC | 90.1 | % | challenge |
| MUSR | 42.9 | % | 0-shot |
| WinoGrande | 76.3 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 58.5，知识推理偏弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [Code Llama 7B 文档地址](https://llama.meta.com/docs/)
- 发布日期: 2023-08-24
- 厂商: Meta
