---
title: "Codestral：完整基准性能指南"
description: "深入分析 Codestral 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-05-29
lastmod: 2024-05-29
draft: false
weight: 10
model_id: "codestral"
vendor: "mistral"
version: "codestral"
tags: ["coding", "open-weights"]
---

# Codestral

## 模型概述

Mistral Codestral 22B 代码专用模型, 32K 上下文, 支持 80+ 编程语言, 代码生成与补全性能突出。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Mistral | codestral | 2024-05-29 | 32K | text | text | MNPL |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 75.1 | % | 5-shot |
| HumanEval | 69.2 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 63.3 | % | 0-shot CoT |
| MATH | 29.4 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 58.3 | % | 3-shot CoT |
| GPQA | 32.4 | % | 0-shot |
| IFEval | 59.4 | % | prompt_strict |
| ARC | 87.4 | % | challenge |
| MUSR | 47.2 | % | 0-shot |
| WinoGrande | 75.8 | % | 0-shot |

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

- 代码生成与调试

## 参考文献

- [Codestral 文档地址](https://docs.mistral.ai/)
- 发布日期: 2024-05-29
- 厂商: Mistral
