---
title: "StarCoder2 3B：完整基准性能指南"
description: "深入分析 StarCoder2 3B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-28
lastmod: 2024-02-28
draft: false
weight: 10
model_id: "starcoder2-3b"
vendor: "other"
version: "starcoder2-3b"
tags: ["open-weights", "coding", "self-hostable"]
---

# StarCoder2 3B

## 模型概述

BigCode StarCoder2 3B 轻量代码模型, 16K 上下文, 3B 参数, 适合边缘设备代码补全任务。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | starcoder2-3b | 2024-02-28 | 16K | text | text | BigCode Open Model License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 60.6 | % | 5-shot |
| HumanEval | 82.1 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.2 | % | 0-shot CoT |
| MATH | 37.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 62.1 | % | 3-shot CoT |
| GPQA | 36.2 | % | 0-shot |
| IFEval | 55.2 | % | prompt_strict |
| ARC | 87.5 | % | challenge |
| MUSR | 38.4 | % | 0-shot |
| WinoGrande | 76.9 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- HumanEval 82.1，代码生成能力出色。

## 劣势

- 闭源专有模型，不支持自托管。
- 上下文窗口 16K 偏小。

## 适用场景

- 代码生成与调试

## 参考文献

- [StarCoder2 3B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-02-28
- 厂商: Other
