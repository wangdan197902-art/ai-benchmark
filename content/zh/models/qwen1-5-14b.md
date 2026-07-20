---
title: "Qwen1.5 14B：完整基准性能指南"
description: "深入分析 Qwen1.5 14B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-02-25
lastmod: 2024-02-25
draft: false
weight: 10
model_id: "qwen1-5-14b"
vendor: "alibaba"
version: "1.5-14b"
tags: ["open-weights", "chinese"]
---

# Qwen1.5 14B

## 模型概述

阿里巴巴 Qwen1.5 14B 中型开源模型, 32K 上下文, 平衡性能与资源, 适合企业级应用。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Alibaba | 1.5-14b | 2024-02-25 | 32K | text | text | Qwen License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 78.4 | % | 5-shot |
| HumanEval | 65.8 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 84.0 | % | 0-shot CoT |
| MATH | 46.2 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 71.6 | % | 3-shot CoT |
| GPQA | 33.9 | % | 0-shot |
| IFEval | 79.9 | % | prompt_strict |
| ARC | 92.7 | % | challenge |
| MUSR | 58.7 | % | 0-shot |
| WinoGrande | 78.6 | % | 0-shot |

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

- [Qwen1.5 14B 文档地址](https://qwenlm.github.io/)
- 发布日期: 2024-02-25
- 厂商: Alibaba
