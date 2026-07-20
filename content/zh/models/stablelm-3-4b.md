---
title: "StableLM 3 4B：完整基准性能指南"
description: "深入分析 StableLM 3 4B 在 MMLU、HumanEval、GSM8K、MATH、BBH 等基准上的表现，包含定价与适用场景。"
date: 2024-06-26
lastmod: 2024-06-26
draft: false
weight: 10
model_id: "stablelm-3-4b"
vendor: "other"
version: "stablelm-3-4b"
tags: ["open-weights", "self-hostable"]
---

# StableLM 3 4B

## 模型概述

Stability AI StableLM 3 4B 模型, 4K 上下文, 多语言 (English/Spanish/German/Italian/French)。

## 核心规格

| 厂商 | 版本 | 发布日期 | 上下文窗口 | 输入模态 | 输出模态 | 许可证 |
|------|---------|-------------|----------------|-----------------|------------------|---------|
| Other | stablelm-3-4b | 2024-06-26 | 4K | text | text | Stability AI Community License |

## 基准测试表现

| 基准 | 得分 | 单位 | 备注 |
|------|------|------|------|
| MMLU (Massive Multitask Language Understanding) | 50.6 | % | 5-shot |
| HumanEval | 32.6 | pass@1 | — |
| GSM8K (Grade School Math 8K) | 48.1 | % | 0-shot CoT |
| MATH | 11.5 | % | 0-shot CoT |
| BBH (BIG-Bench Hard) | 54.9 | % | 3-shot CoT |
| GPQA | 26.8 | % | 0-shot |
| IFEval | 51.6 | % | prompt_strict |
| ARC | 86.8 | % | challenge |
| MUSR | 36.6 | % | 0-shot |
| WinoGrande | 74.1 | % | 0-shot |

## 定价

| 输入 | 输出 | 缓存读取 | 缓存写入 |
|------|--------|-----------|-----------|
| — | — | — | — |

*每百万 token*

## 优势

- 可靠的通用模型。

## 劣势

- MMLU 仅 50.6，知识推理偏弱。
- HumanEval 32.6，代码能力较弱。
- 闭源专有模型，不支持自托管。
- 上下文窗口 4K 偏小。

## 适用场景

- 通用对话与问答

## 参考文献

- [StableLM 3 4B 文档地址](https://huggingface.co/models)
- 发布日期: 2024-06-26
- 厂商: Other
